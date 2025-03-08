# Lưu data về Lark Base

**Bước 1: Tạo tài khoản liên kết.**\
**Cách 1 :** Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là **Lark Base**

{% embed url="https://prnt.sc/7dIQ9j63KuD7" %}

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về **Lark Base**, ở phần **Form đăng ký --> mục Lưu data--> bấm Thêm mới ---> chọn Tạo liên kết ->Loại tài khoản là Lark Base**

![Tài khoản liên kết ](<../../../.gitbook/assets/tài khoản liên kết form.gif>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**App ID, App Secret.** là các thông tin kết nối láy trong tài khoản Larkbase

Ấn **Thêm tài khoản** để Lưu.

{% embed url="https://prnt.sc/VNcNH7-BEOw5" %}

**\*Cách lấy các thông tin kết nối bên** [**Lark Base** ](cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md)

{% content-ref url="cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md" %}
[cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md](cach-tao-app-va-lay-cac-thong-tin-ket-noi-cua-lark-base.md)
{% endcontent-ref %}

#### Bước 3: **Tạo** cấu hình lưu trữ form.

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> Tạo cấu hình form.** Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng

{% embed url="https://prnt.sc/gaw4yRqAt4Ce" %}

**Kết nối các thông tin:**

**Nhập thông tin App Token** lấy trong tài khoản Larkbase và bấm **Kết nối**&#x20;

{% embed url="https://prnt.sc/ArGfVqIHYeyq" %}

**Chọn Table (Bảng dữ liệu) muốn dữ liệu đồng bộ sang bên Lark Base**

{% embed url="https://prnt.sc/XqCDKriRnniV" %}

* **Tên lưu trữ**: là tên gợi nhắc cho cấu hình form này.
* **Table:** Bạn chọn bảng tính bạn muốn lưu trữ dữ liệu về bên Lark Base

{% hint style="info" %}
Bạn cần tạo sẵn các Table ( Bảng dữ liệu) từ bên Lark Base ,  trong mục Cấu hình Form sẽ không có phần tạo Table mới
{% endhint %}

* **Đồng bộ các trường thông tin:**&#x20;

Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bạn cần lấy Tên Lấy Dữ Liệu của các trường của LadiPage như bên dưới:

<figure><img src="../../../.gitbook/assets/tên lấy dữ liệu (2).png" alt=""><figcaption></figcaption></figure>

Bên phải là các trường thông tin bạn tạo trên **Lark Base**

{% embed url="https://prnt.sc/dIDzdg9Np_NE" %}

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

**Bước 4:** Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../../.gitbook/assets/image (183).png>)

**Bước 5:** Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.

{% hint style="danger" %}
Khi cấu hình lưu trữ dữ liệu về Lark Base, bạn muốn lấy các thông số của URL : URL truy cập, các thông số UTM tracking- utm source, utm medium..., bạn cần tạo các tạo các trường đó ở mục liên kết trường dữ liệu ở form LadiPage và Lark Base ở mục Cấu hình form&#x20;
{% endhint %}
