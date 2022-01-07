# Mobile Andoird Automation

This is Appium for Android native app (POC) sample project. 

Design pattern is applied in the framework: Serenity Screenplay

---


### 1. Installation

```
1. JDK 1.8.x or JDK 11.x.x
2. Maven 3.5.x
3. Appium v1.8.1
```

### Command

https://nodejs.org/es/download/
node -v
npm install -g appium
appium -v
where appium
appium
Ctrl+C
appium -p 4725
https://developer.android.com/studio
C:\Users\ninoc\AppData\Local\Android\Sdk
SDK Platforms
SDK Tools
platform-tools
tools
tools/bin
https://www.swtestacademy.com/appium-tutorial/
sdkmanager --version
sdkmanager --list
adb
adb devices
App info:
https://m.apkpure.com/es/app-info/com.princerk.appinfo/download/1-APK
adb shell "dumpsys activity activities | grep ResumedActivity"
https://www.softwaretestinghelp.com/automate-native-app-on-android-device/
iuautomatorviewer
https://unaqaenapuros.wordpress.com/2019/03/13/049-uiautomatorviewer/
npm install -g appium-doctor
appium-doctor --android
ADV Manager
Pixel 3
App metatrader-5:
https://apkcombo.com/metatrader-5-forex-stock-trading/net.metaquotes.metatrader5/download/apk


#### Android Caps
```
appium.platformName = Android
appium.app = src/test/resources/apps/metatrader5.apk
appium.deviceNames = emulator-5554,emulator-5555
appium.appPackage = net.metaquotes.metatrader5
appium.appActivity = net.metaquotes.metatrader5.ui.MainActivity


---
# poc-app
