AdStir PhoneGap / Cordova Sample
=========================
This sample supports Cordova 3.4 or later.

If you use 2.x(2.5 or later), please access below:
Android: https://github.com/ngigroup-developer/AdStirAndroidPhoneGapSample

iOS: https://github.com/ngigroup-developer/AdStiriOSPhoneGapSample

AdStir
 http://ad-stir.com/

AdStir Developer's Guide
 http://wiki.ad-stir.com/

License
----------------
    Copyright 2014 UNITED, inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

Requirements
----------------
* node.js
* cordova-cli (tested in 3.4.1-0.1.0)
* Android SDK (please install all version of platform sdk)
* Xcode Command-line Tools (please install latest version)
* AdStir WebView SDK Android 2.0.0 or later.
* AdStir WebView SDK iOS 2.0.2 or later.

Usage
----------------
1. Copy adstirwebview.jar to platforms/android/libs.
2. Copy AdstirMraidView.h, libAdstirWebView.a to platforms/ios/AdStirSDK.
3. Edit platforms/android/src/com/ad_stir/samples/cordova/AdStirCordovaSample.java.
 * MEDIA-ID and SPOT-NO to yours.
4. Edit platforms/ios/AdStirCordovaSample/Classes/MainViewController.m.
 * MEDIA-ID and SPOT-NO to yours.
