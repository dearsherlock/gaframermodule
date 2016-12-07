 1.download the .coffee file, and copy to the module folder  
 2.The GA track module require jquery lib, so you should add jquery include script in the index.html .
   Find out your xxx.framer folder, open the index.html file, then edit it.
   add <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
   in the <head>.....</head> 
   

 3.In Framer , you can use it like below,   
   {GoogleAnalytics} = require "GoogleAnalytics"  
   GoogleAnalytics.init 'UA-1234567-8'  
  .......  
  GoogleAnalytics.trackPageView '/Wellcome_Home'  
  then you can see the result in GA  
