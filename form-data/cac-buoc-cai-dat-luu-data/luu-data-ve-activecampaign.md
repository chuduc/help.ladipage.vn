# Lưu data về ActiveCampaign

**Bước 1: Tạo tài khoản liên kết.**\
**Cách 1:** Truy cập trang [builder.ladipage.com](http://builder.ladipage.com/), chọn menu **Tích hợp -> Tài khoản liên kết -> Tạo tài khoản liên kết.** Sau đó lựa chọn Loại tài khoản là Active Campaign.

{% embed url="https://prnt.sc/uy3FsdAHAa3U" %}

**Cách 2 :** Truy cập builder chỉnh sửa trang landingpage muốn lưu data về Active Campaign, ở phần **Form đăng ký, mục Lưu data --> bấm Thêm mới --> chọn Tạo liên kết --> Loại tài khoản là Active Campaign.**

![](<../../.gitbook/assets/tài khoản liên kết form.gif>)

**Bước 2:** Nhập đầy đủ các thông tin:

**Tên Liên kết:** là tên để phân biệt với các liên kết khác.&#x20;

**API URL**, **API KEY** là api kết nối lấy trong tài khoản ActiveCampaign của bạn.

Ấn **Thêm tài khoản** để Lưu.

![](<../../.gitbook/assets/image (969).png>)

**\*Cách lấy API URL và API KEY trong ActiveCampaign.**

Đăng nhập tài khoản ActiveCampaign-> Tài khoản ( góc dưới cùng bên tay trái )->Developer

![](<../../.gitbook/assets/image (665).png>)

#### Bước 3: **Tạo** cấu hình lưu trữ form&#x20;

Vào lại trang builder.ladipage.com, chọn menu **Tích hợp -> Cấu hình Form -> Tạo cấu hình form.**

<figure><img src="../../.gitbook/assets/cấu hình form.gif" alt=""><figcaption></figcaption></figure>

Bấm nút **Chọn** để sử dụng tài khoản liên kết bạn muốn dùng&#x20;

![](<../../.gitbook/assets/image (661).png>)

Điền các thông tin ở phần thiết lập cấu hình form&#x20;

![](<../../.gitbook/assets/image (470).png>)

**Đồng bộ các trường thông tin :**

Bạn cần ghép các trường thông tin tương ứng của 2 form với nhau. Bên tay trái là các trường thông tin bạn đã tạo trên form ở landing page, bên phải là các trường thông tin bạn tạo trên ActiveCampaign

Bạn vào builder chỉnh sửa của landing page, Form đăng ký muốn thiết lập lưu trữ, bạn thiết lập đầy đủ trường của form theo ý bạn muốn, ví dụ 4 trường: họ và tên, email, số điện thoại, để lại tin nhắn cho chúng tôi.

Mỗi trường sẽ tương ứng với **1 TÊN LẤY DỮ LIỆU** (như ảnh mô tả )

![](<../../.gitbook/assets/image (682).png>)

Bạn chọn tương ứng các cột **Tên lấy dữ liệu** với các trường ở ActiveCampaign đã tạo của bạn

![](<../../.gitbook/assets/image (634).png>)

Nhập **Tên cấu hình** để lưu lại cấu hình form vừa tạo và bấm nút **Hoàn tất**&#x20;

![](<../../.gitbook/assets/image (182).png>)

Bạn có thể chọn **thêm tài khoản liên kết** khác cho Cấu hình này. Mỗi cấu hình được chứa tối đa 3 tài khoản liên kết, tương đương với 3 nguồn lưu trữ thông tin khách hàng đồng thời nhận được từ form đăng ký trên Landing Page.

**Bước 4:** Quay trở lại form trên trang Landing Page, chọn toàn form bạn đang muốn cài đặt và chọn **"Lưu data":**

![](<../../.gitbook/assets/image (413).png>)

**Bước 5:** Chọn cấu hình phù hợp trong danh sách cấu hình form đã được cài đặt ở bước 3, sau đó bấm **Cập nhật** để hoàn thành.
