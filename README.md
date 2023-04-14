BLUETOOTH LOW ENERGY ADVERTISEMENT SCANNER  
=========================================================================================================                                  
                                                                                                       
This is an html page that uses WEB BLuetooth API witch scan for BLE devices that are advertising.

WEB Bluetooth API are in development and work only on certain browsers and eventually enabling flags on it

This page create a bluetooth navigator and start scan for BLE devices that are advertising data and log 
on screen some informations about the devices and the messages  

This API require a User interaction before start scanning, so i need implement a click function (on the
whole page) to make it work  

WHAT'S NEW:
----------------------------------------------------------------------------------------------------------
-> first version 

TO DO:
----------------------------------------------------------------------------------------------------------
-> make the script start on page load

-> make beacon PARSER working (Just for fun)

-> function to copy the message 

-> broadcast a BLE message (need API development implement send function)

REQUIREMENTS:
----------------------------------------------------------------------------------------------------------

RequestLEScan works with Chrome on Android and Mac with: 
chrome://flags/#enable-experimental-web-platform-features flag enabled