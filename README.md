# Adding SIM Swap Detection to your Flutter Firebase Apps with Firebase Auth & **tru.ID** SIMCheck

## Requirements

- A [tru.ID Account](https://tru.id)
- A mobile phone with a SIM card and mobile data connection
- A [Firebase Account](https://firebase.google.com/console)

## Getting Started

Clone the starter-files branch via:

```bash
git clone -b starter-files --single-branch https://github.com/tru-ID/firebase-phone-auth-sim-swap-detection-flutter.git
```

If you're only interested in the finished code in main then run:

```bash
git clone -b main https://github.com/tru-ID/firebase-phone-auth-sim-swap-detection-flutter.git
```

Create a [tru.ID Account](https://tru.id)

Install the tru.ID CLI via:

```bash
npm i -g @tru_id/cli

```

Input your **tru.ID** credentials which can be found within the tru.ID [console](https://developer.tru.id/console)

Install the **tru.ID** CLI [development server plugin](https://github.com/tru-ID/cli-plugin-dev-server)

Create a new **tru.ID** project within the root directory via:

```
tru projects:create firebase-auth-flutter --project-dir .
```

If you want to create a tru.ID project with Sandbox mode enabled for testing, run:

```bash
tru projects:create firebase-auth-flutter --mode sandbox --project-dir
```

Read more about Sandbox mode [here](https://developer.tru.id/docs/sandbox).

Run the development server, pointing it to the directory containing the newly created project configuration. This will also open up a localtunnel to your development server making it publicly accessible to the Internet so that your mobile phone can access it when only connected to mobile data.

```
tru server -t
```

## Getting started with FlutterFire

This project uses FlutterFire which is a set of Flutter plugins which connect your Flutter application to Firebase. To get your project up and running check out the [overview guide](https://firebase.flutter.dev/docs/overview) and how to get setup for [Android](https://firebase.flutter.dev/docs/installation/android), [iOS](https://firebase.flutter.dev/docs/installation/ios) and [Authentication Setup](https://firebase.flutter.dev/docs/auth/phone).

> **NOTE** Flutter with null safety is preferred.

## Run the app

To start the project, ensure you have a physical device connected then run:

```bash
flutter run
```

> **Note** For a physical iOS device ensure you've [provisioned your project in XCode](https://flutter.dev/docs/get-started/install/macos#deploy-to-ios-devices)

## References

- [**tru.ID** docs](https://developer.tru.id/docs)

## Meta

Distributed under the MIT License. See [LICENSE](https://github.com/tru-ID/passwordless-auth-flutter/blob/main/LICENSE.md)

[**tru.ID**](https://tru.id)
