# iOS12.1 Emoji
Changes systemless-ly the default emojis of your Android device with the ones from iOS 12.1.
This module also changes the system font configuration so the font pack loads the modified emojis.

## Preview of all the iOS12.1 emojis included in this module:
![All included](http://i.imgur.com/Scr2QQq.jpg)
All the included emojis.

## Prerequisites
* Magisk v19 or higher

**_Note:_** 
Tested on the Oneplus X running various android 9 roms with Magisk v19. Your mileage may vary.

## How to download & install this module
Inside [the Magisk manager app](https://play.google.com/store/apps/details?id=com.topjohnwu.magisk) go to the "Downloads" section. 
You can find "iOS12.1 emoji font" listed there. 
Click on the download button (down arrow) and then click on "install". 
Wait a few seconds for the download & installing to finish.  
After installing click on "reboot". Your device should reboot. 

**_Note:_** When you experience problems installing this module check out this [discussion on XDA](https://forum.xda-developers.com/apps/magisk/magisk-ios10-emoji-font-t3596503)

**_Note:_** 
Clear data of your keyboard app to enable ALL the Emoji fonts inside your keyboard app.
You need to use a keyboard which supports Unicode 11 emojis [eg. Gboard]

## How it works
Replaces the default emoji font (NotoColorEmoji.tff) with the iOS12.1 variant. 

## Links
* [Magisk forum](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)
* [Magisk manager app](https://play.google.com/store/apps/details?id=com.topjohnwu.magisk)
* [Manual zip download](https://drive.google.com/drive/folders/0BzOEHiXH09zFTnVKNjAtZUVlR3c?usp=sharing)
* [Discussion on XDA](https://forum.xda-developers.com/apps/magisk/magisk-ios10-emoji-font-t3596503)
* [Bug report](https://github.com/Magisk-Modules-Repo/Magisk-ios10-Emoji-font/issues/new)
* [Github](https://github.com/Magisk-Modules-Repo/Magisk-ios10-Emoji-font)
* [Donate](http://paypal.me/jeanpierrewolters/5)

## Changelog
#### version 9.0
* Updated module to support Magisk v19

#### version 8.0
* Updated emojis to iOS 12.1 Beta 2
* Update to Magisk version 1700

#### version 7.5
* Update to Magisk version 1500

#### version 7.3
* Updated for magisk v14.0
* Updated script

#### version 7.1
* oops.. fixed typo on the HTC font file :)

#### version 7
* New emoji font
* Fix for samsung & HTC roms.
* Template V4

#### version 6
* Saftey net breaks in magisk v13 beta so this is a temp fix by disabeling the post fs data script.
* Disabled  post-fs-data script
* Disabled Dynamic fonts.xml
* Disabled Dynamic fallback_fonts.xml

#### version 5
* Added  post-fs-data script
* Dynamic fonts.xml
* Dynamic fallback_fonts.xml

#### version 4
* Updated font file
* Some typo's fixed
* Updated support links

#### version 3
* Updated module for magisk v11.6

#### version 2
* Name updated
* Description added
* Added Donate link

#### version 1
* Initial Release
