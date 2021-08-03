[![Maven Central](https://img.shields.io/maven-central/v/app.screeb.sdk/android-sdk.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22app.screeb.sdk%22%20AND%20a:%22android-sdk%22)

__:warning:  Android SDK has been released in beta. Please contact us [here](https://screeb.app/get-a-demo-of-screeb/) to request a demo.__

___

## Android demo app for the Screeb SDK

This app contains all necessary installation and configuration you need to start using Screeb in your Android app.

You'll find :

- Install examples in the build.gradle files.
- Initial configuration in `DemoApplication.kt`
- Additional commands in `MainActivity.kt`

## How to install the Android SDK in your app ?

To install the sdk, you just need to add the repository `mavenCentral` in your project `build.gradle` file if not present yet :

```groovy
allprojects {
    repositories {
        mavenCentral()
    }
}
```

Then add this dependency in your app `build.gradle` :

```groovy
implementation 'app.screeb.sdk:android-sdk:0.6'
```

## How to configure the Android SDK
[See here.](https://github.com/ScreebApp/developers/wiki/android-SDK-install)

## Technical requirements

The Screeb sdk is configured to work with Android sdk version 17 minimum

The size of the sdk is approximately 500 Kb

The sdk needs the permissions `ACCESS_NETWORK_STATE` and `INTERNET` to work well

## Dependencies

We try to update the dependencies very frequently, if you have a any problem, please create an issue in this repository.

- kotlin-stdlib:1.5.21
- kotlinx-coroutines-android:1.5.1
- core-ktx:1.6.0
- appcompat:1.3.1
- material:1.4.0
- constraintlayout:2.0.4
- room-runtime:2.3.0
- retrofit:2.9.0
- converter-moshi:2.9.0
- logging-interceptor:4.9.1
- conscrypt-android:2.2.1
- lifecycle-runtime-ktx:2.3.1
- lifecycle-extensions:2.2.0
- dagger:2.30.1
- threetenabp:1.3.1
- glide:4.12.0
- emoji-material:0.7.0
- emoji-twitter:0.7.0
