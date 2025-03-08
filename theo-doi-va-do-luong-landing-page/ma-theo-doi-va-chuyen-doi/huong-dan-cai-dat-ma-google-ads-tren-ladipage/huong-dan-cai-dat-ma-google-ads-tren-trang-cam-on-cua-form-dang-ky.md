# Hướng dẫn cài đặt mã Google ads trên trang cảm ơn của form đăng ký

Trong trường hợp bạn sử dụng trang cảm ơn sau khi điền form đăng ký ở landingpage, ngoài ID google ads, bạn cần cài đặt thêm mã theo dõi sự kiện trên trang cảm ơn.

## &#x20;**Bước 1: Tạo ID Google Ads**

Truy cập tài khoản Google Ads và làm theo các bước dưới đây để lấy Google Ads ID:

![](<../../../.gitbook/assets/image (99).png>)

![](<../../../.gitbook/assets/image (512).png>)

![](<../../../.gitbook/assets/image (548).png>)

![](<../../../.gitbook/assets/image (292).png>)

![](<../../../.gitbook/assets/image (312).png>)

**Phần ID này thiết lập cho cả trang gốc landingpage  điền form và trang landing page cảm ơn.**

![](<../../../.gitbook/assets/image (137).png>)

## **Bước 2: Tạo hành động chuyển đổi trên Google Ads**

Nếu bạn đang cần theo dõi hành động hoàn tất form đăng ký hoặc hành động nhấp chuột vào một nút nào đó trên trang, thì trước tiên bạn cần Thiết lập Hành động chuyển đổi đó trên Google Ads trước. Các bước thực hiện như sau:

![Vào phần "Công cụ và cài đặt" rồi chọn phần "Lượt chuyển đổi"](<../../../.gitbook/assets/image (510).png>)

![Tạo một hành động chuyển đổi mới](<../../../.gitbook/assets/image (525).png>)

![](<../../../.gitbook/assets/image (284).png>)

![](<../../../.gitbook/assets/image (291).png>)

![](<../../../.gitbook/assets/image (311).png>)

![](<../../../.gitbook/assets/image (113).png>)

![](<../../../.gitbook/assets/image (296).png>)

![](<../../../.gitbook/assets/image (552).png>)

## **Bước 3 : Gắn đoạn mã sự kiện vào TRANG LANDINGPAGE CẢM ƠN**&#x20;

Sau khi tạo đoạn mã sự kiện thành công, bạn copy đoạn mã, cho vào phần THIẾT LẬP- MÃ JAVASCRIPT/CSS- TRƯỚC THẺ HEAD của trang cảm ơn, không cần gắn ở trang gốc( trang chứa form đăng ký) phần mã sự kiện này&#x20;

![](<../../../.gitbook/assets/image (511).png>)

{% hint style="info" %}
Lưu ý : Khi sử dụng trang cảm ơn sau khi điền form, thì bạn KHÔNG gắn mã sự kiện cho phần form đăng ký, chỉ sử dụng gắn mã sự kiện ở trang cảm ơn của bạn.
{% endhint %}

![](<../../../.gitbook/assets/image (294).png>)
