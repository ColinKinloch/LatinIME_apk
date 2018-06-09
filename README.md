# LatinIME_apk
Gradle configuration to compile the AOSP keyboard "LatinIME" to an android apk package.

## Download Build
https://gitlab.com/ColinKinloch/LatinIME_apk/-/jobs/artifacts/master/raw/build/outputs/apk/debug/LatinIME-debug.apk?job=build

## Install
```
git clone https://github.com/ColinKinloch/LatinIME_apk.git
cd LatinIME_apk
git submodule update --init --recursive
TARGET_BUILD_APPS=true ./gradlew installDebug
```
