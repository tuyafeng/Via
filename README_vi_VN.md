# Via Browser - Lựa chọn tốt nhất của dân công nghệ

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

English | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | [日本語](./README_ja_JP.md) | [Русский](./README_ru_RU.md) | [العربية](./README_ar_AR.md) | [Tiếng Việt](./README_vi_VN.md)

### Giới thiệu Via Browser là một trình duyệt mạnh mẽ với các tính năng sau:
 - Thuần túy & không quảng cáo 
 - Tùy chỉnh cao - Nhanh như chớp
 - Nhỏ gọn nhưng tuyệt vời 

Hãy thử và bạn sẽ không bao giờ hối hận :)

[Tải xuống từ Google Play](https://play.google.com/store/apps/details?id=mark.via.gp)

[Tải xuống phiên bản toàn cầu](https://res.viayoo.com/v1/via-release.apk)

[Tải xuống phiên bản Trung Quốc](https://res.viayoo.com/v1/via-release-cn.apk)

### Hỗ trợ bản địa hóa

Chúng tôi khuyến khích mọi người cùng tham gia hỗ trợ bản địa hóa. Sau đây là cách thực hiện:

1. Sao chép kho lưu trữ này (fork)
2. Sao chép tệp `app/src/main/res/values/strings.xml` vào đường dẫn như `app/src/main/res/values-%(lang)/`, thay thế `%(lang)` bằng [*mã ngôn ngữ ISO 639-1*](http://www.loc.gov/standards/iso639-2/php/code_list.php)
3. Dịch tệp `app/src/main/res/values-%(lang)/strings.xml`
4. Tạo yêu cầu kéo (Pull Request)

### Câu hỏi thường gặp

**Via sử dụng công cụ kết xuất nào?**

Via sử dụng trình kết xuất WebView tích hợp sẵn trên nền tảng Android. Trên các thiết bị Android 5.0 trở lên, phiên bản WebView thường là `Android System WebView (com.google.android.webview)`, bạn có thể cập nhật nó trong Play Store để có trải nghiệm duyệt web tốt hơn. Nếu bạn muốn biết phiên bản WebView hiện tại và phiên bản của thiết bị, bạn có thể nhấp vào "Cài đặt - Giới thiệu" trong Via và chạm vào biểu tượng Via để xem thông tin gỡ lỗi, trong đó có thông tin về WebView.

**Làm thế nào để tắt JavaScript hoặc thiết lập tác nhân người dùng đặc biệt cho một trang web?**

Mở trang web, nhấp vào biểu tượng kính lúp hoặc biểu tượng khiên ở bên trái thanh địa chỉ, sau đó bạn có thể cấu hình riêng.

Hoặc mở "Cài đặt - Chung - Cấu hình trang web" để thêm cấu hình thủ công.

**Tôi không muốn chặn quảng cáo trên một trang web nhất định.**

Vui lòng tham khảo câu hỏi trước, bạn có thể tắt chặn quảng cáo cho trang web đó trong cấu hình trang web.

**Tại sao Via không thể lưu mật khẩu?**

Rất tiếc, Google đã loại bỏ tính năng này khỏi WebView. Bạn có thể thử sử dụng ứng dụng tự động điền (Bitwarden, KeePass, v.v.) nếu phiên bản Android trên thiết bị của bạn cao hơn hoặc bằng 8.0.

**Tại sao Via không thể quét mã QR?**

~~Có quá nhiều ứng dụng có thể quét mã QR, và tôi không muốn thêm một chức năng trùng lặp như vậy. Bạn có thể quét mã QR bằng ứng dụng camera trên điện thoại của mình.~~

Từ phiên bản 4.3.4, Via đã thêm trình quét mã QR tích hợp.

**Làm thế nào để liên hệ với tôi?**

Bạn có thể liên hệ với tôi trên [Twitter](https://twitter.com/Yafeng78600505) và tôi sẽ trả lời sớm nhất có thể.

Bạn cũng có thể [mở một vấn đề](https://github.com/tuyafeng/Via/issues/new) trên GitHub, và tôi sẽ kiểm tra và trả lời các vấn đề khoảng một lần một tuần.

Bạn có thể gửi email cho tôi [tại đây](mailto:yafengtu@gmail.com) nếu cần, nhưng tôi rất tiếc là có thể tôi sẽ không trả lời.