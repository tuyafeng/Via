# Via Browser - Geekのベストチョイス

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | 日本語

### 紹介
Via Browserは、以下の機能を備えた強力なブラウザです。

- ピュア＆広告なし
- 高度にカスタマイズ可能
- 稲妻のように速い
- 小さくて繊細な

ダウンロードして試してください:)

[Google Playから入手する](https://play.google.com/store/apps/details?id=mark.via.gp)
[國際版の入手](https://res.viayoo.com/v1/via-release.apk)
[中国版の入手](https://res.viayoo.com/v1/via-release-cn.apk)

### ローカライズに協力する
私たちは、誰でもローカライズに協力できるように奨励しています。以下は具體方法で。
1. このリポジトリをフォークする
2. `app/src/main/res/values/strings.xml` を `app/src/main/res/values-%(lang)/` のようなパスにコピーします。[*ISO を使用することを忘れないでください。 639-1 言語コード*](http://www.loc.gov/standards/iso639-2/php/code_list.php) `%(lang)` を置き換えます
3. `app/src/main/res/values-%(lang)/strings.xml`を翻訳します。
4. プロジェクトに PR を送信する。

### よくある問題
***Viaはどのレンダリングエンジンを使用していますか?***

Viaは、Androidプラットフォームに含まれる組み込みのWebViewレンダラーを使用しています。Android 5.0以降のデバイスでは、WebViewの実装は通常Android System WebView (com.google.android.webview)であり、Playストアで更新すると、より良いブラウジング体験が得られます。デバイスの現在のWebViewの実装とバージョンを知りたい場合は、Viaで「設定 - このアプリについて」をクリックし、Viaのロゴをタップしてデバッグ情報を取得できます。デバッグ情報にはWebViewの情報が含まれています。

***特定のWebサイトでJavaScriptを無効にしたり、特別なユーザーエージェントを設定したりするにはどうすればいいですか?***

サイトを開き、アドレスバーの左側にある虫眼鏡または盾のアイコンをクリックし、個別に設定できます。または、「設定 - 一般 - サイト設定」を開いて、手動で設定を追加することもできます。

***特定のサイトで広告ブロックを無効にしたいです。***

前述の質問を参照してください。サイト設定でサイトの広告ブロックをオフにできます。

***Viaはなぜパスワードを保存できないのですか？***

残念ながら、GoogleはWebViewからこの特定の機能を削除しました。デバイスのAndroidバージョンが8.0以上であれば、自動入力アプリ（Bitwarden、KeePassなど）を試すことができます。

***ViaはなぜQRコードをスキャンできないのですか？***

~~QRコードをスキャンできるアプリケーションは多すぎるため、そのような繰り返し機能を追加したくありません。電話のカメラアプリでQRコードをスキャンできます。~~

バージョン4.3.4から、Viaは組み込みのQRコードスキャナーを追加しました。

*** どうやってあなたに連絡できますか？***
[Twitter](https://twitter.com/Yafeng78600505) または [Weibo](https://weibo.com/u/7558014976) でご連絡いただければ、できるだけ早く返信させていただきます。

Github で [問題を提起](https://github.com/tuyafeng/Via/issues/new) することもできます。私は通常、週に 1 回問題を確認して返信します。

必要に応じて、[メール](mailto:yafengtu@gmail.com) をお送りいただくこともできますが、申し訳ありませんが、返信できない場合があります。
