# require_bluetooth_le

Cordova/Phonegap plugin to insert a tag for \<uses-feature android:name="android.hardware.BLUETOOTH_LE" android:required="true"\> into your AndroidManifest.xml file in order to require the phone to have BLE hardware in order to run.  This will prevent your app from showing up in the app store on old phones w/o the necessary hardware.

Add this to your config.xml to enable

<gap:plugin name="cordova-plugin-require-bluetoothle" source="npm" version="1.0.0" />
