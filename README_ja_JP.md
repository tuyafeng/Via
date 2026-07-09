# Via Browser - Geekのベストチョイス

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | 日本語 | [Русский](./README_ru_RU.md) | [العربية](./README_ar_AR.md) | [বাংলা](./README_bn_IN.md) | [한국어](./README_ko_KR.md)

## 紹介

Via Browser は、以下の機能を備えた強力なブラウザです。

- ピュア＆広告なし
- 高度にカスタマイズ可能
- 稲妻のように速い
- 小さくても素晴らしい

ダウンロードして試してください。後悔することはありませんよ :)

[Google Playから入手する](https://play.google.com/store/apps/details?id=mark.via.gp)

[グローバル版をダウンロード](https://res.viayoo.com/v1/via-release.apk)

[中国版をダウンロード](https://res.viayoo.com/v1/via-release-cn.apk)

### ローカライズに協力する

ローカライズへの協力をお待ちしています。以下が具体的な手順です。

1. このリポジトリをフォークする
2. `app/src/main/res/values/strings.xml` を `app/src/main/res/values-%(lang)/` のようなパスにコピーします。`%(lang)` を [*ISO 639-1 言語コード*](http://www.loc.gov/standards/iso639-2/php/code_list.php) に置き換えてください。
3. `app/src/main/res/values-%(lang)/strings.xml` を翻訳します。
4. プルリクエストを送信してください。

### よくある質問

**Viaはどのレンダリングエンジンを使用していますか？**

Viaは、Androidプラットフォームに含まれる組み込みのWebViewレンダラーを使用しています。Android 5.0以降のデバイスでは、WebViewの実装は通常 `Android System WebView (com.google.android.webview)` であり、Playストアでアップデートするとよりよいブラウジング体験が得られます。デバイスの現在のWebView実装とバージョンを知りたい場合は、Viaで「設定 - このアプリについて」をクリックし、Viaのロゴをタップしてデバッグ情報を取得できます。デバッグ情報にはWebView情報が含まれています。

**特定のWebサイトでJavaScriptを無効にしたり、特別なユーザーエージェントを設定したりするにはどうすればいいですか？**

サイトを開き、アドレスバーの左側にある虫眼鏡または盾のアイコンをクリックすると、個別に設定できます。

または、「設定 - 一般 - サイト設定」を開いて、手動で設定を追加することもできます。

**特定のサイトで広告ブロックを無効にしたいです。**

前述の質問を参照してください。サイト設定でそのサイトの広告ブロックをオフにできます。

**Viaはなぜパスワードを保存できないのですか？**

残念ながら、GoogleはWebViewからこの機能を削除しました。デバイスのAndroidバージョンが8.0以上の場合、自動入力アプリ（Bitwarden、KeePassなど）を使用してみてください。

**ViaはなぜQRコードをスキャンできないのですか？**

~~QRコードをスキャンできるアプリケーションが多すぎるため、そのような重複機能を追加したくありませんでした。電話のカメラアプリでQRコードをスキャンできます。~~

バージョン4.3.4から、Viaは組み込みQRコードスキャナーを追加しました。

**どうやって作者に連絡できますか？**

[Twitter](https://twitter.com/Yafeng78600505) でご連絡いただければ、できるだけ早く返信させていただきます。

GitHubで [問題を提起](https://github.com/tuyafeng/Via/issues/new) することもできます。通常、週に1回程度問題を確認して返信しています。

必要であれば、[メール](mailto:yafengtu@gmail.com) でご連絡いただくこともできますが、申し訳ありませんが、返信できない場合があります。
