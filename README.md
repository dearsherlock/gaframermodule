 1.download the .coffee file, and copy to the module folder  
 2.In Framer , you can use it like below,   
   {GoogleAnalytics} = require "GoogleAnalytics"  
   GoogleAnalytics.init 'UA-1234567-8'  
  .......  
  GoogleAnalytics.trackPageView '/Wellcome_Home'  
  then you can see the result in GA  
