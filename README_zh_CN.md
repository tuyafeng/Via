# Via 浏览器 - 探索速度与简约的极限

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

### 简介

Via 浏览器是一个有着如下特点的强大浏览器:

- 纯净 & 无广告
- 可高度定制化
- 快如闪电
- 体积小过一张照片

下载看看咯 :)

[在 Google Play 下载](https://play.google.com/store/apps/details?id=mark.via.gp)

[下载 Play 版本](https://res.viayoo.com/v1/via-release.apk)

[下载中文版本](https://res.viayoo.com/v1/via-release-cn.apk)

### 助力本地化

我们鼓励所有人来帮助和完善本地化工作，以下是具体步骤：

1. Fork 这个仓库
2. 复制 `app/src/main/res/values/strings.xml` 到类似 `app/src/main/res/values-%(lang)/` 的路径， 别忘记用 [*ISO 639-1 语言代码*](http://www.loc.gov/standards/iso639-2/php/code_list.php) 替换 `%(lang)`
3. 翻译 `app/src/main/res/values-%(lang)/strings.xml`
4. 提交 PR 到这个项目

### 常见问题

**Via 的渲染引擎是什么？**

Via 使用的是 Android 内建的 WebView 渲染网页。在 Android5.0 及以上的设备，WebView 通常是通过 `Android System WebView(com.google.android.webview)` 实现，你可以在应用商店更新它以获得更好的浏览体验。如果你想要了解设备当前 WebView 的实现和版本，可以点击 Via 的「设置 - 关于 - 版本」查看。

**怎么为某个特定站点关闭 JS 或设置特定的 UA？**

打开那个站点，点击地址栏左侧的放大镜或盾牌图标，接着就可以单独设置那个网站了。

或者打开「设置 - 通用 - 网站设定」，手动添加某个网站的配置项。

**我不想拦截某个站点的广告。**

参考上一条，你可以在网站设定中为某个特定站点关闭广告拦截。

**为什么 Via 无法保存密码？**

很不幸，Google 从 WebView 中移除了这个特性。在 Android8.0 及以上的设备，你可以使用自动填充应用（例如 Bitwarden、Keepass 等）来保存和填充密码。

**为什么 Via 无法扫码？**

~~可以扫码的工具实在太多了，我不想为 Via 添加如此重复的功能。请直接使用你设备上的相机应用扫码。~~

从 4.3.4 版本开始，Via 添加了内建二维码扫描器。

**怎么联系你？**

你可以在[推特](https://twitter.com/Yafeng78600505)或[微博](https://weibo.com/u/7558014976)上联系我，我会尽快回复。

你也可以在 Github 上[提 issue](https://github.com/tuyafeng/Via/issues/new)，我通常每周会查看并回复一次 issues。

实在必要的话，你也可以[发邮件](mailto:yafengtu@gmail.com)，但很抱歉，我可能不会回复。

