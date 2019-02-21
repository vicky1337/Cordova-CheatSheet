# Cordova-CheatSheet
 
APACHE CORDOVA CHEAT SHEET


1.Create Project $ cordova create hello com.example.hello HelloWorld 

2.Add Platform $ cordova platform add ios $ cordova platform add android

3.List Platform $ cordova platforms ls $ cordova platform rm android 

4. Build $ cordova build $ cordova build ios

5. Plugin Search $ cordova plugin search bar code com.phonegap.plugins.barcodescanner - Scans Barcodes

6. Basic device information (Device API): $ cordova plugin add org.apache.cordova.device 

7.Network Connection and Battery Events: $ cordova plugin add org.apache.cordova.network-information $ cordova plugin add org.apache.cordova.battery-status

8.Accelerometer, Compass, and Geolocation: $ cordova plugin add org.apache.cordova.device-motion $ cordova plugin add org.apache.cordova.device-orientation $ cordova plugin add org.apache.cordova.geolocation 

9.Camera, Media playback and Capture: $ cordova plugin add org.apache.cordova.camera $ cordova plugin add org.apache.cordova.media-capture $ cordova plugin add org.apache.cordova.media 

10.Access files on device or network (File API): $ cordova plugin add org.apache.cordova.file $ cordova plugin add org.apache.cordova.file-transfer 

11.Notification via dialog box or vibration: $ cordova plugin add org.apache.cordova.dialogs $ cordova plugin add org.apache.cordova.vibration 

12.Contacts: $ cordova plugin add org.apache.cordova.contacts 

13.Globalization: $ cordova plugin add org.apache.cordova.globalization 

14.Splashscreen: $ cordova plugin add org.apache.cordova.splashscreen 

15.Open new browser windows (InAppBrowser): $ cordova plugin add org.apache.cordova.inappbrowser

16.Debug console: $ cordova plugin add org.apache.cordova.console

17.Plugin List $ cordova plugin ls # or 'plugin list' 

18. Remove Plugin $ cordova plugin rm org.apache.cordova.console
