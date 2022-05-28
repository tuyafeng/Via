# Via Browser - Geek's Best Choice

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

English | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md)

### Introduction

Via Browser is a powerful browser with following features:

- Pure & adless
- Highly customizable
- Fast like lightning
- Small, yet awesome

Try it and you will never regret :)

[Get it from Google Play](https://play.google.com/store/apps/details?id=mark.via.gp)

[Download Global Version](https://res.viayoo.com/v1/via-release.apk)

[Download Chinese Version](https://res.viayoo.com/v1/via-release-cn.apk)

### Help with localization

We encourage everyone to help with localization. The following is how to do.

1. Fork this repository
2. Copy `app/src/main/res/values/strings.xml` to path like `app/src/main/res/values-%(lang)/`, replace `%(lang)` with [*the ISO 639-1 language code*](http://www.loc.gov/standards/iso639-2/php/code_list.php)
3. Translate `app/src/main/res/values-%(lang)/strings.xml`
4. Make a Pull Request

### FAQ

**Which rendering engine does Via use?**

Via uses the built-in WebView renderer included on the Android platform. On Android 5.0+ devices, the WebView implementation is usually `Android System WebView (com.google.android.webview)`, you can update it in the Play Store for a better browsing experience. If you want to know the current WebView implementation and version of your device, you can click "Settings - About" in Via and tap on the Via logo to get the debugging information which contains the WebView information.

**How to disable JavaScript or set a special user agent for a website?**

Open the site, click the magnifying glass or shield icon on the left side of the address bar, and then you can configure it separately.

Or open "Settings-General-Site Configuration" to add configuration manually.

**I don’t want to block ads on a certain site.**

Please refer to the previous question, you can turn off ad blocking for the site in the site configuration.

**Why can't Via save the password?**

Unfortunately, Google removed this particular feature from WebView. You can try using the autofill app(Bitwarden, KeePass, etc.) if the Android version of your device is higher than or equal to 8.0.

**Why can't Via scan the QR code?**

~~There are too many applications that can scan QR codes, and I don’t want to add such a repetitive function. You can scan the QR code with your phone's camera app.~~

Starting from version 4.3.4, Via has added a built-in QR code scanner.

**How to contact you?**

You can contact me on [Twitter](https://twitter.com/Yafeng78600505) and I will reply as soon as possible.

You can also [open an issue](https://github.com/tuyafeng/Via/issues/new) on GitHub, and I will check and reply to issues about once a week.

You can email me [here](mailto:yafengtu@gmail.com) if must, but I'm sorry I may not respond.

