# **ESP Library2 v1.0 � March 19, 2020**
*Added support for ESP Specification 3.005 (includes V1 Gen2)
*Complete rewrite of the ESP Library. 
    *To interact with a V1, create an instance of the ESPClient and register a ESPClientListener to receive ESP data.
    *To scan for VRI Bluetooth device use the BluetoothScanner.
        *Register a BTScanListener to received scanned device.

# **ESP Library2 v2.0.1 � January 26, 2021**
*Added support for reading the RSSI of the connected remote BLE device.
*Fixed a bug in InfDisplayData that falsely indicated active alerts when in use with a V1 Gen2 thats operating with Custom Frequencies enabled. The method isAlertPresent() has been marked deprecated.
*The ESP packet ResponseSerialNumber has been refactored.
*BluetoothScanner was modify to address potential NPEs.
*The gradle version for HelloV1 has been changed to '4.0.1'
