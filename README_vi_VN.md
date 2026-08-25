# Via Browser - Lựa chọn hàng đầu của dân sành công nghệ

<div align="center"><img src="http://viayoo.com/en/images/logo.png" alt="Via Logo" height="100"/></div>

[English](./README.md) | [简体中文](./README_zh_CN.md) | [繁體中文](./README_zh_TW.md) | [Português](./README_pt_BR.md) | [Español](./README_es_ES.md) | [Türkçe](./README_tr_TR.md) | [日本語](./README_ja_JP.md) | [Русский](./README_ru_RU.md) | [العربية](./README_ar_AR.md) | [Tiếng Việt](./README_vi_VN.md)

### Giới thiệu

Via Browser là trình duyệt mạnh mẽ với các tính năng sau: 
- Giao diện thuần khiết, không quảng cáo 
- Khả năng tùy biến cao 
- Tốc độ nhanh như chớp 
- Nhỏ gọn nhưng cực kỳ ấn tượng 

Hãy thử trải nghiệm và bạn sẽ không bao giờ hối tiếc :)

[Tải xuống từ Google Play](https://play.google.com/store/apps/details?id=mark.via.gp)

[Tải xuống phiên bản toàn cầu](https://res.viayoo.com/v1/via-release.apk)

[Tải xuống phiên bản Trung Quốc](https://res.viayoo.com/v1/via-release-cn.apk)

### Hỗ trợ dịch thuật

Chúng tôi khuyến khích mọi người cùng tham gia vào quá trình dịch thuật. 
Dưới đây là các bước thực hiện: 

1. Fork kho mã nguồn (repository) này 
2. Sao chép tệp `app/src/main/res/values/strings.xml` vào đường dẫn có dạng `app/src/main/res/values-%(lang)/`, trong đó thay thế `%(lang)` bằng [*mã ngôn ngữ ISO 639-1*](http://www.loc.gov/standards/iso639-2/php/code_list.php) 
3. Dịch nội dung tệp `app/src/main/res/values-%(lang)/strings.xml` 
4. Tạo một Pull Request

### Các câu hỏi thường gặp 

**Via sử dụng công cụ kết xuất (rendering engine) nào?** 

Via sử dụng công cụ kết xuất WebView tích hợp sẵn trên nền tảng Android. Trên các thiết bị chạy Android 5.0 trở lên, thành phần WebView thường là `Android System WebView (com.google.android.webview)`; bạn có thể cập nhật nó trên Play Store để có trải nghiệm duyệt web tốt hơn. Nếu muốn biết phiên bản và thành phần WebView hiện tại trên thiết bị, bạn có thể vào mục "Cài đặt - Giới thiệu" (Settings - About) trong Via và chạm vào biểu tượng Via để xem thông tin gỡ lỗi (debugging information), trong đó có chứa thông tin về WebView. 

**Làm thế nào để tắt JavaScript hoặc thiết lập User Agent riêng cho một trang web?**

 Hãy mở trang web đó, nhấn vào biểu tượng kính lúp hoặc hình khiên ở bên trái thanh địa chỉ, sau đó bạn có thể tùy chỉnh cấu hình riêng cho trang đó. Hoặc vào mục "Cài đặt - Chung - Cấu hình trang web" (Settings - General - Site Configuration) để thêm cấu hình thủ công. 

**Tôi không muốn chặn quảng cáo trên một trang web cụ thể.**

 Vui lòng tham khảo câu hỏi phía trên; bạn có thể tắt tính năng chặn quảng cáo cho trang web đó trong phần cấu hình trang web. 

**Tại sao Via không thể lưu mật khẩu?**

 Rất tiếc, Google đã loại bỏ tính năng này khỏi WebView. Bạn có thể thử sử dụng các ứng dụng tự động điền (như Bitwarden, KeePass, v.v.) nếu thiết bị của bạn chạy Android phiên bản 8.0 trở lên. 

**Tại sao Via không thể quét mã QR?**

 ~~Có quá nhiều ứng dụng có thể quét mã QR, và tôi không muốn thêm một tính năng trùng lặp như vậy. Bạn có thể quét mã QR bằng ứng dụng camera trên điện thoại của mình.~~ Kể từ phiên bản 4.3.4, Via đã bổ sung tính năng quét mã QR tích hợp sẵn. 

**Làm thế nào để liên hệ với bạn?** 

Bạn có thể liên hệ với tôi qua [Twitter](https://twitter.com/Yafeng78600505) và tôi sẽ phản hồi sớm nhất có thể. 

Bạn cũng có thể [tạo một issue](https://github.com/tuyafeng/Via/issues/new) trên GitHub; tôi sẽ kiểm tra và phản hồi các vấn đề khoảng một lần mỗi tuần. 

Bạn có thể gửi email cho tôi [tại đây](mailto:yafengtu@gmail.com) nếu cần thiết, nhưng rất tiếc là tôi có thể sẽ không phản hồi.