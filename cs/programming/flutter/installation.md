# Flutter
- Install from officail website
- Use the command to check what is required for development
  ```
  $ flutter doctor
  ```

  ```
    Running "flutter pub get" in flutter_tools...                       8.1s
    Doctor summary (to see all details, run flutter doctor -v):
    [✓] Flutter (Channel stable, 2.10.2, on macOS 12.1 21C52 darwin-x64, locale en-TW)
    [✗] Android toolchain - develop for Android devices
        ✗ Unable to locate Android SDK.
        Install Android Studio from: https://developer.android.com/studio/index.html
        On first launch it will assist you in installing the Android SDK components.
        (or visit https://flutter.dev/docs/get-started/install/macos#android-setup for detailed instructions).
        If the Android SDK has been installed to a custom location, please use
        `flutter config --android-sdk` to update to that location.

    [✗] Xcode - develop for iOS and macOS
        ✗ Xcode installation is incomplete; a full installation is necessary for iOS development.
        Download at: https://developer.apple.com/xcode/download/
        Or install Xcode via the App Store.
        Once installed, run:
            sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
            sudo xcodebuild -runFirstLaunch
        ✗ CocoaPods not installed.
            CocoaPods is used to retrieve the iOS and macOS platform side's plugin code that responds to your plugin usage on the Dart side.
            Without CocoaPods, plugins will not work on iOS or macOS.
            For more info, see https://flutter.dev/platform-plugins
        To install see https://guides.cocoapods.org/using/getting-started.html#installation for instructions.
    [✓] Chrome - develop for the web
    [!] Android Studio (not installed)
    [✓] IntelliJ IDEA Ultimate Edition (version 2021.3.2)
    [✓] VS Code (version 1.64.2)
    [✓] Connected device (1 available)
    [✓] HTTP Host Availability

    ! Doctor found issues in 3 categories.
    ➜  client git:(main) ✗ flutter --versi
  ```

# XCode Installation
- Install XCode developer tool from APP store
  - Run the following codes (check by flutter doctor) after installation is done
  ```
  $ sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
  $ sudo xcodebuild -runFirstLaunch
  ```

# Cocoa Installation
- Install by following the instruction
  - https://guides.cocoapods.org/using/getting-started.html#installation

