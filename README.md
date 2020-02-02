# google-maps-sdk
Google Maps SDK for Android v3 BETA

For hosting a maven artifact of the .aar library.

See [Google docs](https://developers.google.com/maps/documentation/android-sdk/v3-client-migration) to migrate your app.

Instead of copying the maps-sdk-3.0.0-beta.aar to your project, add this maven artifact to your dependencies.

Add the JitPack repository to your root build.gradle file at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Add the dependency:

```
dependencies {
    implementation 'com.github.jeffdgr8:google-maps-sdk:v3.0.0-beta'
}
```
