# dpt

Docker Packaging Tool instead of APT. PaaC(package as a container)!

build apk without complex installation:

```sh
$ dpt-get install android
$ docker-android ./gradlew assemblePhoneDebug
```

Launch various android studio :

```sh
$ dpt-get install android-studio:1.5.0
$ android-studio

$ dpt-get install android-studio:2.2.0-beta
$ android-studio

$ dpt-get update-alternative android:1.5.0
$ android-studio
```
