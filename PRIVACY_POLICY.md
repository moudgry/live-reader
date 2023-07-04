## QR & Barcode Scanner - Live Reader: Privacy policy

Welcome to QR & Barcode Scanner - Live Reader app for Android!

This is an Android application developed by Mahmoud ElGharably. The app is available on GitHub under the MIT license, It is also available on Google Play.

In fact, I take privacy very seriously because I know how irritating it is when apps collect your data without your knowledge.

This app does not collect any personally identifiable information. All data (such as history and bookmarks) created by you (the user) is stored only on your device, and can be erased by simply clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

https://github.com/moudgry/live-reader/blob/main/AndroidManifest.xml#L7-L15

<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.CAMERA` | This is required to scan barcodes and QR codes. You, as the user, or the system, can revoke this permission at any time from Settings. Revoking this permission will prevent the app from using your camera to scan barcodes and QR codes. |
| `android.permission.VIBRATE` | Required to vibrate the device when perform scan. Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.READ_EXTERNAL_STORAGE` | This permission can be revoked by the system or the user at any time. This is only required if you want to import the app's data from CSV file. In order to read the CSV file, the app needs permission to read the storage. Importing data from CSV file but revoking this permission later may cause the app to crash at the time of choosing the CSV file because a security exception occurred while reading the CSV file. |
| `android.permission.WRITE_EXTERNAL_STORAGE` | This is required to export the application data to a CSV file.|
| `android.permission.INTERNET` | Required to launch website automatically after scanning. Permission automatically granted by the system; can't be revoked by user. |

 <hr style="border:1px solid gray">

If you find any vulnerability caused by me unintentionally, or have any question regarding how the app protects your privacy, please send me an email or post a discussion on GitHub, I will definitely try to fix it and help you.

All the best,<br/>
Mahmoud ElGharably<br/>
moud.elgharably@gmail.com<br/>
https://moudgry.github.io
