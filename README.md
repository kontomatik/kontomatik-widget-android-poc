# Introduction
This example shows how in the simplest way embed the Kontomatik Widget into an Android mobile application. Below you will find the steps required to run the example on your computer.

# Prerequisites
Set up Android Studio Dev Environment taking with following functions:
* Android SDK, Android SDK Platform, Performance (Intel ® HAXM), Android Virtual Device
* Android 9 (Pie) SDK 
* Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image
* Android SDK Build-Tools - 28.0.3

# Running the Program
**Step 1** – Clone project from this repository to Android Studio

**Step 2** - Go to `app/src/main/assets/index.html` and look for param passed to the `embedKontomatik` function and change the value of the `client` parameter to your own client id provided by Kontomatik

**Step 3** - Press play on the top of the screen to run the application on an emulator.

**Step 4** - Proceed with testing the widget and login to a bank, using mock credentials "test" -> "Test123". If the login is successful session values will be displayed in a Toast Notification.
