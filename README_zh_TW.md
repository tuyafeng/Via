# Via 瀏覽器 - 探索速度與簡約的極限

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | 繁體中文 | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | [日本語](./README_ja_JP.md)

### 簡介

Via 瀏覽器是一個擁有下列特色的強大瀏覽器：

- 純淨極簡以及無廣告
- 高度可自訂化
- 快如閃電
- 小而精巧

試試看它，您不會後悔的 :)

[從 Google Play 取得](https://play.google.com/store/apps/details?id=mark.via.gp)

[下載國際(Play 商店)版本](https://res.viayoo.com/v1/via-release.apk)

[下載中文版本](https://res.viayoo.com/v1/via-release-cn.apk)

### 協助在地化

我們鼓勵每個人來協助在地化。下方是具體的步驟：

1. 派生(Fork)此存放庫(Repository)
2. 複製 `app/src/main/res/values/strings.xml` 至如同 `app/src/main/res/values-%(lang)/` 的路徑，用 [*ISO 639-1 語言代碼*](http://www.loc.gov/standards/iso639-2/php/code_list.php) 取代 `%(lang)`
3. 翻譯 `app/src/main/res/values-%(lang)/strings.xml`
4. 建立提取要求(Pull Request)

### 常見問題

**Via 的渲染引擎是什麼？**

Via 使用的是 Android 平台內建的 WebView 渲染網頁。 在 Android 5.0 以上的裝置，WebView 通常是透過 `Android System WebView(com.google.android.webview)` 實現，您可以在 Play 商店更新它以取得更好的瀏覽體驗。 如果您想要知道您的裝置目前 WebView 的實作和版本，您可以點選 Via 的「設定 - 關於」再點選頁面中的 Via 標誌檢視除錯資訊，WebView 的資訊就在其中。

**如何為特定網站停用 JavaScript 或設定特別的使用者代理(User Agnet)？**

打開那個網站，點擊網址欄左側的放大鏡或盾牌圖示，就可以分開設定它了。

或是開啟「設定 - 一般 - 網站設定」，手動新增特定網站的設定。

**我不想封鎖某個特定網站的廣告。**

請參照上一個問題，您可以在網站設定中為那個網站關閉廣告封鎖。

**為什麼 Via 無法儲存密碼？**

很不幸地，Google 從 WebView 移除了這個功能。 在 Android 8.0 以及以上的裝置，您可以使用自動填入應用程式（例如 Bitwarden、Keepass 等）來儲存和填入密碼。

**為什麼 Via 無法掃描二維碼(QR code)？**

~~可以掃描二維碼的應用程式實在太多了，我不想為 Via 增加如此重複的功能。 請直接使用您手機上的相機程式掃描二維碼。~~

從 4.3.4 版本開始，Via 新增了內建二維碼掃描器。

**如何聯絡你？**

您可以在[Telegram](https://t.me/tuyafeng)上聯絡我，我會盡快回覆。

您也可以在 GitHub 上[提出問題 (Issue)](https://github.com/tuyafeng/Via/issues/new)，我通常每週會查看並回覆一次問題。

如果有必要的話，您也可以[寄送電子郵件](mailto:yafengtu@gmail.com)，但很抱歉，我可能不會回覆。
