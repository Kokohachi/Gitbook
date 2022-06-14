# トラブルシューティングガイド

<details>

<summary>インストールについて</summary>

<mark style="color:purple;">**説明どおりにやってもAltStoreがインストールされない！**</mark>

**以下の事項を確認してください：**

_**・パソコンでiOSデバイスを信頼しましたか？**_

_**Macの場合：**_ Finder (macOS 10.15 Catalina 以降) か iTunes (macOS 10.14 Mojave 以下) かでMacに繋がれているか確認し、信頼していない場合そこで信頼してください。

_**Windowsの場合：**_iOSデバイスの、設定→一般→リセット→プライバシーと位置情報のリセット からリセットして、PCに繋ぎ直してください。

**・AltStore用に新しくApple ID を作ってもOKです。**

</details>

### Sign-In

#### <mark style="color:purple;">AltStore freezes/takes forever to sign-in.</mark>

This could happen for a number of reasons. If you’re experiencing this issue, please check the following:

* Are you on public/work/school WiFi? If so, your WiFi might be preventing devices from discovering each other. Try connecting your computer to your phone’s hotspot and trying again. (If you're using an iPad, make sure it's connected to your hotspot as well.)
* Have you said “Trust” on both your Mac and iOS device after connecting your device to your Mac? You can check by Finder (macOS 10.15 Catalina or later) or iTunes (macOS 10.14 Mojave and earlier) and seeing if a dialog box pops up asking if you want to trust your phone.
* (Windows) Firewall might be blocking incoming network connections to AltServer. You must enable network access for AltServer in your firewall settings for it to receive refreshed apps from AltStore.
* (Windows) Did you install iTunes or iCloud from the Microsoft Store? If so, you’ll need to uninstall them and download the latest versions directly from Apple.
* You may need to make sure iTunes and iCloud are running on your computer as well.
* Finally, try plugging your iPhone or iPad into your computer. This should fix all connectivity problems, but does mean AltStore may not be able to automatically refresh apps for you in the background over WiFi.

### AltServer

<mark style="color:purple;">**AltStore says “Could not find AltServer” when trying to sideload or refresh apps.**</mark>

AltServer must be running on a computer connected to the same WiFi as AltStore in order to sideload or refresh apps. If AltServer is running on the same WiFi network as AltStore and you're still receiving this error, try the following:

* Are you on public/work/school WiFi? If so, your WiFi might be preventing devices from discovering each other. Try connecting your computer to your phone’s hotspot and trying again. (If you're using an iPad, make sure it's connected to your hotspot as well.)
* Have you said “Trust” on both your Mac and iOS device after connecting your device to your Mac? You can check by Finder (macOS 10.15 Catalina or later) or iTunes (macOS 10.14 Mojave and earlier) and seeing if a dialog box pops up asking if you want to trust your phone.
* (Windows) Your firewall might be blocking incoming network connections to AltServer. You must enable network access for AltServer in your firewall settings for it to receive refreshed apps from AltStore.
* (Windows) Did you install iTunes or iCloud from the Microsoft Store? If so, you’ll need to uninstall them and download the latest versions directly from Apple.
* Finally, try plugging your iPhone or iPad into your computer. This should fix all connectivity problems, but does mean AltStore may not be able to automatically refresh apps for you in the background over WiFi.

#### <mark style="color:purple;">I’m unable to change my network settings to allow devices to communicate with each other (such as on school/work/public WiFi).</mark>

You can always sideload and refresh apps without WiFi by plugging your iPhone or iPad into your computer. However, this means AltStore may not be able to refresh apps for you in the background over WiFi.
