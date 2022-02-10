# Via Brauzer - Geekning eng yaxshi tanlovi

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

### Kirish

Via Brauzer - bu quyidagi xususiyatlarga ega kuchli brauzer:

- Sof & reklamasiz
- Yuqori darajada moslashtirilgan
- Chaqmoq kabi tez
- Kichik, lekin ajoyib

Uni sinab ko‘ring va hech qachon afsuslanmaysiz :)

[Google Play orqali yuklab olish](https://play.google.com/store/apps/details?id=mark.via.gp)

[Global versiyasini yuklab olish](https://res.viayoo.com/v1/via-release.apk)

[Xitoy versiyasini yuklab olish](https://res.viayoo.com/v1/via-release-cn.apk)

### Mahalliylashtirish bo‘yicha yordam

Biz hammani mahalliylashtirish bo‘yicha yordam berishga chaqiramiz. Qanday qilish kerakligi quyida keltirilgan.

1. Fork bo‘limini oching
2. `app/src/main/res/values/strings.xml` faylidan `app/src/main/res/values-%(lang)/` kabi yo‘lga nusxa oling, `%(lang)` uni [*the ISO 639-1 language code*](http://www.loc.gov/standards/iso639-2/php/code_list.php) bilan almashtiring
3. Tarjima qiling `app/src/main/res/values-%(lang)/strings.xml`
4. Pull Request tugmasini bosing

### Ko‘p beriladigan savollar

**Via qaysi renderlash mexanizmidan foydalanadi?**

Via Android platformasiga kiritilgan o‘rnatilgan WebView renderidan foydalanadi. Android 5.0+ qurilmalarida WebView ilovasi odatda `Android System WebView (com.google.android.webview)` bo‘lib, yanada yaxshi ko‘rish tajribasi uchun uni Play Marketda yangilashingiz mumkin. Agar siz joriy WebView ilovasi va qurilmangiz versiyasini bilmoqchi bo‘lsangiz, WebView maʼlumotlarini o‘z ichiga olgan nosozliklarni tuzatish maʼlumotlarini olish uchun Via brauzerida "Sozlamalar - Via haqida" tugmasini bosing va Via logosiga teging.

**Qanday qilib JavaScript’ni o‘chirish yoki veb-sayt uchun maxsus foydalanuvchi agentini o‘rnatish mumkin?**

Saytni oching, manzil satrining chap tomonidagi kattalashtiruvchi oyna yoki qalqon belgisini bosing va keyin uni alohida sozlashingiz mumkin.

yoki konfiguratsiyani qo‘lda qo‘shish uchun "Sozlamalar-Umumiy-Sayt konfiguratsiyasi" bo‘limini oching.

**Men ma’lum bir saytdagi reklamalarni bloklashni xohlamayman.**

Iltimos, oldingi savolga qarang, siz sayt konfiguratsiyasida sayt uchun reklama bloklanishini o‘chirish imkoniga egasiz.

**Nega Via parolni saqlay olmaydi?**

Afsuski, Google bu xususiyatni WebView ilovasidan olib tashladi. Agar qurilmangizning Android versiyasi 8.0 dan yuqori yoki unga teng bo‘lsa, avtomatik to‘ldirish ilovasidan (Bitwarden, KeePass va hk.) foydalanib ko‘rishingiz mumkin.

**Nima uchun Via QR kodini skanerlashi mumkin emas?**

~~QR kodlarni skaner qiluvchi ilovalar juda ko‘p va men bunday takrorlanuvchi funksiyani qo‘shishni istamayman. QR kodni telefoningiz kamera ilovasi yordamida ham skanerlashingiz mumkin.~~

4.3.4 versiyasidan boshlab Via o‘rnatilgan QR kod skanerini qo‘shdi.

**Siz bilan qanday aloqaga chiqish mumkin?**

Siz men bilan [Twitter](https://twitter.com/Yafeng78600505) orqali aloqaga chiqishingiz mumkin va men imkon qadar tezroq javob beraman.

Shuningdek, siz GitHub saytida [muammo ochish](https://github.com/tuyafeng/Via/issues/new)ingiz mumkin va men haftada bir marta tekshirib, savollarga javob beraman.

Agar kerak bo‘lsa, [menga email](mailto:yafengtu@gmail.com) orqali xabar yuborishingiz mumkin, lekin javob bermasligimdan afsusdaman.

