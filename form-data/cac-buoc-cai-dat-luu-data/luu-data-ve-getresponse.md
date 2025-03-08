# Lưu data về GetResponse

**Bước 1: Tạo tài khoản liên kết.**\
**Cách 1 :** Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là GetResponse.

{% embed url="https://prnt.sc/Ai11SHaYrMg9" %}

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về GetResponse, ở phần **Form đăng ký --> mục Lưu data--> bấm Thêm mới ---> chọn Tạo liên kết ->Loại tài khoản là** GetResponse.

![Tài khoản liên kết ](<../../.gitbook/assets/tài khoản liên kết form.gif>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API KEY**: là api key kết nối lấy trong tài khoản GetResponse.

Ấn Thêm tài khoản để Lưu.

![](<../../.gitbook/assets/image (459).png>)

**\*Cách lấy API KEY của GetResponse**

Đăng nhập tài khoản GetResponse, di chuột vào biểu tượng MENU tài khoản ở phía trên góc phải màn hình, chọn Tích hợp và API (Intergrations and API).

<figure><img src="../../.gitbook/assets/get2 (1).png" alt=""><figcaption></figcaption></figure>

#### Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> Tạo cấu hình form.** Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùn&#x67;**.**

<figure><img src="../../.gitbook/assets/cấu hình form.gif" alt=""><figcaption></figcaption></figure>

**Kết nối các thông tin:**

![](<../../.gitbook/assets/image (1004).png>)

* **Tên lưu trữ**: là tên gợi nhắc cho cấu hình form này.
* **Campaign:** Bạn chọn campaign trong danh sách campaign của Getresponse mà bạn muốn data về.
* **Đồng bộ các trường thông tin:**&#x20;

Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bạn cần lấy Tên Lấy Dữ Liệu của các trường của LadiPage như bên dưới:

<figure><img src="../../.gitbook/assets/tên lấy dữ liệu (2).png" alt=""><figcaption></figcaption></figure>

Bên phải là các trường thông tin bạn tạo trên GetRespons&#x65;**:** Bạn sử dụng các **trường mặc định của Getresponse, riêng trường Số điện thoại hoặc các trường  bạn tạo trên LadiPage không có trường mặc định tương ứng  trên Getresponse thì bạn cần tạo trường tùy chỉnh như sau:**

Bạn vào phần Custom fields (Trường tùy chỉnh) --> Create custom field (tạo trường tùy chỉnh).

<figure><img src="../../.gitbook/assets/get5.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/get6.png" alt=""><figcaption></figcaption></figure>

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

**Bước 4:** Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (183).png>)

**Bước 5:** Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.

Data trả về Getresponse ở phần List --> bạn chọn đúng Campaign đã kết nối để kiểm tra data.

<figure><img src="../../.gitbook/assets/get7.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**Lưu ý:**

* Form đăng ký bắt buộc phải có trường Email và sử dụng trường Email mặc định của Getresponse.
{% endhint %}
