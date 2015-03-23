# Imei-phonegap-plugin
cordova phonegap plugin for android

Get your device  IMEI number.

CLI Install:

cordova plugin add https://github.com/satishSKY/Imei-phonegap-plugin.git

 Usage:
 
  window.plugins.imei.get(function(iemi){
          console.log(iemi);
          },function(e){
              console.log(e);
          });
