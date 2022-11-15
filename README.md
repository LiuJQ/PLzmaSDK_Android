# PLzmaSDK_Android
A simple project to demostrate how to build PLzmaSDK for Android

## How To Build
- Step 1
  - Clone PLzmaSDK source project
  ```shell
    git submodule update --init --recursive
  ```

- Step 2
  - Make sure gradle sync successfully
  - Just run the app for debugging
  - Build release shared library
  ```shell
    gradle assembleRelease
  ```
  
- Step 3
  - Where to get built so files
  ```text
    The artifacts are placed in directory: app/build/intermediates/cmake/debug(or release)/obj
  ```

## PLzmaSDK Source Project
[PLzmaSDK](https://github.com/OlehKulykov/PLzmaSDK)
Thanks to author of PLzmaSDK, and this is a very useful project.