# Via Browser - Geek'in En İyi Seçimi

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | Türkçe

### Tanıtım

Via Browser, aşağıdaki özelliklere sahip güçlü bir tarayıcıdır:

- Saf ve reklamsız
- Son derece özelleştirilebilir
- Şimşek gibi hızlı
- Küçük ama harika

Deneyin ve asla pişman olmayacaksınız :)

[Google Play'den İndirin](https://play.google.com/store/apps/details?id=mark.via.gp)

[Global Versiyonu İndirin](https://res.viayoo.com/v1/via-release.apk)

[Çin Versiyonu İndirin](https://res.viayoo.com/v1/via-release-cn.apk)

### Yerelleştirme ile ilgili yardım

Herkesi yerelleştirme konusunda yardım etmeye davet ediyoruz. Aşağıdaki adımları takip edin.

1. Bu repoyu forkla
2. `app/src/main/res/values/strings.xml` dosyasını `app/src/main/res/values-%(lang)/` gibi bir yola kopyalayın, `%(lang)` yerine [*ISO 639-1 dil kodu*](http://www.loc.gov/standards/iso639-2/php/code_list.php)
3. `app/src/main/res/values-%(lang)/strings.xml` dosyasını çevirin
4. Pull Request gönderin

### SSS

**Via hangi render motorunu kullanıyor?**

Via, Android platformunda bulunan yerleşik WebView oluşturucuyu kullanır. Android 5.0+ cihazlarda, WebView uygulaması genellikle `Android System WebView (com.google.android.webview)` şeklindedir, daha iyi bir tarama deneyimi için Play Store'dan güncelleyebilirsiniz. Cihazınızın mevcut WebView uygulamasını ve sürümünü öğrenmek istiyorsanız, Via'da "Ayarlar - Hakkında" seçeneğine tıklayabilir ve WebView bilgilerini içeren hata ayıklama bilgilerini almak için Via logosuna dokunabilirsiniz.

**JavaScript nasıl devre dışı bırakılır veya bir web sitesi için özel bir kullanıcı aracısı nasıl ayarlanır?**

Siteyi açın, adres çubuğunun sol tarafındaki büyüteç veya kalkan simgesine tıklayın ve ardından ayrı olarak yapılandırabilirsiniz.

Veya yapılandırmayı manuel olarak eklemek için "Ayarlar - Genel - Site yapılandırması"nı açın.

**Belirli bir sitedeki reklamları engellemek istemiyorum.**

Lütfen bir önceki soruya bakın, site yapılandırmasında site için reklam engellemeyi kapatabilirsiniz.

** Via şifreyi neden kaydedemiyor?**

Ne yazık ki, Google bu özelliği WebView'dan kaldırdı. Cihazınızın Android sürümü 8.0 veya daha yüksekse otomatik doldurma uygulaması (Bitwarden, KeePass vb.) kullanmayı deneyebilirsiniz.

**Neden Via karekod tarayamıyor?**

~~QR kodlarını tarayabilen çok fazla uygulama var ve bu kadar tekrar eden bir işlev eklemek istemiyorum. Karekodu telefonunuzun kamera uygulamasıyla tarayabilirsiniz.~~

Via, 4.3.4 sürümünden itibaren yerleşik bir karekod tarayıcı ekledi.

**Nasıl iletişim kurabilirim?**

[Twitter](https://twitter.com/Yafeng78600505) üzerinden benimle iletişime geçebilirsiniz, mümkün olan en kısa sürede cevap vereceğim.

Ayrıca GitHub'da [bir issue açabilirsiniz](https://github.com/tuyafeng/Via/issues/new) ve sorunları haftada bir kez kontrol edip yanıtlayacağım.

Gerekirse bana [buradan](mailto:yafengtu@gmail.com) e-mail gönderebilirsiniz, ancak üzgünüm yanıt veremeyebilirim.
