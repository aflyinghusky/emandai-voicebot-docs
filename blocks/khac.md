# Khác

## Điều kiện <a href="#id-4tgmcablivlo" id="id-4tgmcablivlo"></a>

Sử dụng khối này để tạo các quy tắc hoặc bộ quy tắc hành động cho AI BOT

**Ví dụ**&#x20;

Xét kịch bản tặng quà ưu đãi khi khách hàng mua đạt số lượng cụ thể. Nếu số lượng khách hàng mua nhiều hơn 3 sẽ được tặng voucher trị giá 1 triệu đồng

<table data-header-hidden><thead><tr><th width="150"></th><th width="349.83589462129527"></th><th></th></tr></thead><tbody><tr><td><strong>Đối tượng</strong></td><td><strong>Phản hồi</strong></td><td><strong>Ý định / Điều kiện</strong></td></tr><tr><td>USER</td><td>Vậy anh đặt 4 máy rửa bát nhé</td><td><p>- ý định: "dong_y_mua"</p><p>- quantity = 4</p></td></tr><tr><td>AI BOT</td><td>Quý khách đã đạt đủ số lượng để nhận quà từ EM&#x26;AI là một Voucher mua hàng trị giá 1 triệu đồng. Quà tặng sẽ được giao cùng sản phẩm ạ</td><td>- Điều kiện phản hồi: quantity >3</td></tr></tbody></table>

Theo kịch bản trên, kịch bản thiết lập sẽ như sau:&#x20;

![](../.gitbook/assets/19)

**Cách thiết lập**

(1) Kéo thả khối Điều kiện vào Canvas & chọn ô “Tên điều kiện” để hiển thị giao diện cấu hình \[1]

(2) Nhập tên điều kiện \[2]

(3) Chọn tạo Quy tắc / Bộ quy tắc tùy theo kịch bản \[3]

(4) Thiết lập điều kiện cho quy tắc \[4]

* Và: Tất cả các quy tắc phải thõa
* Hoặc: Thỏa một trong các quy tắc

(5) Thiết lập quy tắc \[5]

(6) Chọn Lưu để hoàn tất \[6]

![](../.gitbook/assets/20)

(7) Tạo kết nối với điều kiện / ý định / khối hành động tương ứng

## Kết thúc hội thoại <a href="#wzg5647n152" id="wzg5647n152"></a>

Sử dụng khối này để tạo điểm kết thúc của luồng hội thoại.

**Cách thiết lập**

(1) Kéo thả khối Kết thúc hội thoại vào Canvas \[1]

(2) Tạo kết nối với ý định / khối phản hồi AI BOT là điểm kết thúc hội thoại \[2]
