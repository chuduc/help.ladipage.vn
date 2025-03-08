# Đồng bộ thông tin về phần KHÁCH HÀNG của Haravan

Ngoài trường hợp đưa thông tin form đăng ký landing page về phần Đơn hàng Haravan, khách hàng cũng có thể lựa chọn đưa thông tin về phần Khách hàng Haravan.&#x20;

Trường hợp này áp dụng khi bạn tạo 1 form đăng ký trên landingpage về các thông tin của khách hàng: tên,email, số điện thoại, ngày tháng năm, địa chỉ - KHÔNG có trường sản phẩm Haravan.

**Bước 1: Tạo tài khoản liên kết**\
Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là Haravan

<figure><img src="../../.gitbook/assets/Haravan.png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API URL:** Đường dẫn trang quản lý Haravan của bạn.

<figure><img src="../../.gitbook/assets/haravan2 (1).png" alt=""><figcaption></figcaption></figure>

Ấn **(Tiếp tục)** để Lưu tài khoản liên kết.

![](<../../.gitbook/assets/image (278).png>)

#### Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> Tạo cấu hình form.** Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng&#x20;

<figure><img src="../../.gitbook/assets/haravan3 (1).png" alt=""><figcaption></figcaption></figure>

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất.**&#x20;

![](<../../.gitbook/assets/image (403).png>)

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

**Bước 4:** Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (759).png>)

{% hint style="info" %}
**Lưu ý:**&#x20;

* **5** trường thông tin trên form có thể sử dụng tích hợp đưa thông tin về mục Khách hàng Haravan: name, email, phone, date, địa chỉ và tỉnh/thành-quận/huyện-phường/xã.
* 1 trong 2 trường email/phone là trường thông tin bắt buộc.
* Định dạng trường "date" khách hàng cần điền vào form: YYYY-MM-DD hoặc YYYY/MM/DD.
* Nếu chỉ có trường địa chỉ mà KHÔNG có trường tỉnh/thành-quận/huyện-phường/xã thì dữ liệu ĐỊA CHỈ sẽ không về Haravan.
{% endhint %}

Vậy là bạn đã hoàn thành việc đồng bộ đơn hàng từ Landing Page sang  mục **Khách hàng trên Haravan.**

![](<../../.gitbook/assets/image (824).png>)

