![iphone-mockup-scene](https://user-images.githubusercontent.com/47140660/119092043-8d2f9d00-ba2b-11eb-90ce-a6e5468de51e.png)

## ABOUT

There are a lot of doc scanning applications available for mobile platforms but most of them either lack quality or variety in features and filters they provide. On top of this most of these applications demand login data and also collect user data, which compromises user security and privacy. Also some other applications like OCR and language translation are available separately from the doc scanning applications, whereas they are often required after scanning a document. Further, after the ban on widely popular doc scanning utility CamScanner by the Indian government, due to security concerns, other apps have been unable to achieve the same quality and variety in features as CamScanner.

## ABOUT

There are a lot of doc scanning applications available for mobile platforms but most of them either lack quality or variety in features and filters they provide. On top of this most of these applications demand login data and also collect user data, which compromises user security and privacy. Also some other applications like OCR and language translation are available separately from the doc scanning applications, whereas they are often required after scanning a document. Further, after the ban on widely popular doc scanning utility CamScanner by the Indian government, due to security concerns, other apps have been unable to achieve the same quality and variety in features as CamScanner.



## How to run this app////////

Install [Flutter](https://flutter.dev) and all required dev tools.

Fetch this repository and navigate to the project directory.

```
cd scanbot-sdk-example-flutter/
```

Fetch and install the dependencies of this example project via Flutter CLI:

```
flutter pub get
```

Connect a mobile device via USB and run the app.

**Android:**

```
flutter run -d <DEVICE_ID>
```

You can get the IDs of all connected devices via `flutter devices`.

**iOS:**

Install Pods dependencies:

```
cd ios/
pod install --repo-update
```

Open the **workspace**(!) `ios/Runner.xcworkspace` in Xcode and adjust the *Signing / Developer Account* settings.
Then build and run the app in Xcode.


## Please note

The Scanbot SDK will run without a license for one minute per session!

After the trial period has expired all Scanbot SDK functions as well as the UI components (like Document Scanner UI) will
stop working or may be terminated. You have to restart the app to get another trial period.

To get an unrestricted, "no-strings-attached" 30 day trial license, please submit the [Trial License Form](https://scanbot.io/en/sdk/demo/trial) on our website.
