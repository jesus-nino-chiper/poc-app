# Mobile Andoird Automation

This is Appium for Android native app (POC) sample project. 

Design pattern is applied in the framework: Serenity Screenplay

---


### 1. Installation

```
1. JDK 1.8.x
2. Maven 3.5.x
3. Appium v1.8.1
```

### Convert JDK from EXE to ZIP
https://bgasparotto.com/convert-jdk-exe-zip

### Download 7-Zip
https://www.7-zip.org/download.html

### 2. Environment settings

Have an android emulator or real device connected

### Download app
https://apkcombo.com/metatrader-5-forex-stock-trading/net.metaquotes.metatrader5/download/apk

### Tutorial app
https://www.swtestacademy.com/appium-tutorial/

#### Android Caps
```
appium.platformName = Android
appium.app = src/test/resources/apps/metatrader5.apk
appium.deviceNames = emulator-5554,emulator-5555
appium.appPackage = net.metaquotes.metatrader5
appium.appActivity = net.metaquotes.metatrader5.ui.MainActivity


---
# poc-app
