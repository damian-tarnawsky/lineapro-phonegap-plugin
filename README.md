# lineapro-phonegap-plugin

Using DTDevices SDK v2.2 (29/09/2017)
Fixes issue related to drivers licenses with invalid data (eg old New Mexico drivers licenses)

## Quick start

To start plugin need to execute 'LineaProCDV.initDT()' method.
Recommended to add this into 'deviceready' handler.

###

!!! You must add section "SupportedExternalAccessoryProtocols" into "[Project Name].plist" file.
This section should include the following items:

- com.datecs.linea.pro.msr
- com.datecs.iserial.communication
- com.datecs.pinpad
- com.datecs.linea.pro.bar

## Device support

Universal plugin for following devices:

- PPAD 1.0
- MPED-400
- BluePad-500
- BluePad-50
- Infinea TAB mini
- Infinea TAB 4
- Infinea TAB
- Linea Pro 5
- Linea Pro 4
- Linea Pro 6
- PP-60
- iSerial
- Linea-Pro

## Supported features:

- Automatically device connection
- Log all events
- Start/Stop Barcode methods

## Additional info

Using iOS SDK from https://ipcmobile.com/products/ios-peripherals/infinea-tab-m/
