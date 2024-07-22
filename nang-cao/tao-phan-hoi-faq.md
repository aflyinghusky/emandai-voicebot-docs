# Tạo phản hồi FAQ

Tính năng phản hồi FAQ giúp AI Bot trả lời các câu hỏi của khách hàng nằm ngoài kịch bản chính, cung cấp thêm thông tin từ bộ tri thức đã được dựng sẵn để linh hoạt trả lời các câu hỏi và giảm thiểu khả năng phản hồi chưa đúng với ý định của khách hàng.&#x20;

Tính năng phản hồi FAQ được áp dụng cho các block [**Khách hàng phản hồi (User Say**](../blocks/luot-hoi-thoai.md)**)** và **Khách hàng phản hồi nâng cao (User says Advanced).**&#x20;

## **Tạo ý định FAQ**

### **Bước 1:** Tạo ý định FAQ

Chọn tab Bối cảnh (TRANG CHỦ / XÂY DỰNG KỊCH BẢN / KỊCH BẢN (V1.0) / BỐI CẢNH), nhấn vào nút TẠO MỚI.

![](../.gitbook/assets/0.png)

### **Bước 2:** Cài đặt Tạo mới ý định FAQ

1. Từ trang Tạo mới, nhấn vào **Ý định** tại **(02).**
2. Nhấn chọn ô **FAQ** tại **(2.1)**

<figure><img src="../.gitbook/assets/1.png" alt=""><figcaption></figcaption></figure>

1. Nhập tên **Ý định FAQ** tại **(2.2)** để đặt tên ý định FAQ
2. Nhập tên **Tiêu đề nút** tại **(2.3)**
3. Nhấn chọn ô **Quay trở lại flow của ý định này sau khi trả lời một FAQ** tại **(2.4)**_(Không bắt buộc)_
4. Nhập **Mô tả** tại **(2.5)** _(Không bắt buộc)_

<figure><img src="../.gitbook/assets/2.png" alt=""><figcaption></figcaption></figure>

5\. Lăn chuột đến cuối trang, nhấn vào nút **LƯU** để lưu ý định FAQ.

### **Bước 3:** Thêm câu mẫu cho ý định FAQ

1. Từ trang Bối cảnh, nhấn vào ý định FAQ cần thêm câu mẫu hoặc nhấn vào biểu tượng **Bút chì.**

<figure><img src="../.gitbook/assets/4.png" alt=""><figcaption></figcaption></figure>

2\. Nhấn vào **Mẫu** tại **(03)** để thêm câu mẫu cho ý định FAQ

![](../.gitbook/assets/5.png)

3\. Nhấn vào nút **TẠO MỚI** tại **(3.1)** để tiến hành thêm câu mẫu trên Pop-up **Câu mẫu** như hình dưới.

4\. Nhập nội dung câu mẫu ở ô **Nội dung** tại **(3.2)**

5\. Nhấn chọn thêm ý định cho câu mẫu vừa tạo tại **(3.3)** nếu muốn. _(Không bắt buộc)_

6\. Nhấn nút **LƯU** tại **(3.4)** để lưu câu mẫu.

![](../.gitbook/assets/6.png)

### **Bước 4:** Thêm phản hồi cho ý định FAQ

1. Lăn chuột xuống cuối trang, nhấn vào mục Phản hồi tại **(04)**
2. Nhấn vào nút THÊM BLOCK tại **(4.1)**

<figure><img src="../.gitbook/assets/7.png" alt=""><figcaption></figcaption></figure>

3\. Nhấn vào mũi tên tại **(4.2)** để đi đến cài đặt chi tiết cho phản hồi

![](../.gitbook/assets/8.png)

4\. Nhấn nút **TẠO PHẢN HỒI** tại **(4.3)** để hiện pop-up Phản hồi

![](../.gitbook/assets/9.png)

5\. Nhập tên phản hồi trong ô **TÊN** tại **(4.4)**

6\. Nhập nội dung phản hồi tại ô **VĂN BẢN** tại **(4.5)**

7\. Nhấn nút **LƯU** tại **(4.6)** để lưu phản hồi.

![](../.gitbook/assets/10.png)

8\. Nhấn dấu **X** để đóng pop-up.

9\. Nhấn nút **LƯU** tại **(05)** để lưu cài đặt.

![](../.gitbook/assets/11.png)

## **Tạo phản hồi FAQ**

### **Bước 1:** Kích hoạt phản hồi FAQ:

1. Từ thanh công cụ (bên trái), thực hiện kéo, thả khối User say/ User say (advance) vào Canvas.
2. Nhấp chuột vào block, hệ thống sẽ hiển thị thiết lập **Cấu hình chung.** _(Xem hình 1)_

<figure><img src="../.gitbook/assets/12.png" alt=""><figcaption></figcaption></figure>

_Hình 1: Bật cài đặt Cấu hình chung - phản hồi FAQ._

### **Bước 2:** Chọn phản hồi FAQ

Tick chọn vào ô **Phản hồi FAQ** tại **(01)** để làm hiện cài đặt Phản hồi FAQ. _(Xem hình 2)_

* Để hủy chọn Phản hồi FAQ, nhấn vào **(1.1), bộ cài đặt FAQ** tại **(02)** sẽ biến mất.

### **Bước 3:** Tùy chỉnh số lần lặp lại FAQ

Chỉ nhập **chữ số** vào **Số lần lặp lại phản hồi FAQ** tại **(2.1)** để giới hạn số lần bot phản hồi FAQ. _(Xem hình 2)_

* Nếu người dùng **để trống** số lần lặp lại, bot sẽ phản hồi FAQ **không giới hạn**.

### **Bước 4:** Nhập nội dung hỏi lại

Nhập nội dung hỏi lại tại (**2.2)**, số ký tự giới hạn là 1000. _(Xem hình 2)_

* Nếu **để trống** nội dung hỏi lại, bot sẽ trả lời FAQ xong và **không phản hồi nội dung lặp lại** nhưng vẫn tiếp tục đợi khách hàng phản hồi tiếp trong bối cảnh đang diễn ra hội thoại
* Nếu muốn thêm nội dung hỏi lại, vui lòng bấm vào **(2.3)**. Khi tạo nhiều nội dung hỏi lại khác nhau, các phản hồi này sẽ được **lựa chọn ngẫu nhiên** để phản hồi khách hàng trong cuộc hội thoại thực tế

### **Bước 5:** Lưu cài đặt FAQ

Người dùng bấm vào nút **Lưu** tại **(03)** để lưu cài đặt Phản hồi FAQ. _(Xem hình 2)_

<figure><img src="../.gitbook/assets/13.png" alt=""><figcaption><p><em>Hình 2: Cài đặt và lưu cài đặt phản hồi FAQ.</em></p></figcaption></figure>

* Block nào được Lưu cài đặt Phản hồi FAQ thì sẽ hiện “Phản hồi FAQ” ngay dưới tag chọn ý định.

_**(Xem Hình 3)**_

<figure><img src="../.gitbook/assets/14.png" alt=""><figcaption><p><em>Hình 3: Giao diện của 1 block có cài đặt phản hồi FAQ.</em></p></figcaption></figure>

* **Thêm tính năng Copy/ Paste khối cho V2:** Tính năng cho phép người dùng có thể dùng thao tác nhấn tổ hợp phím Ctrl C, Ctrl V để sao chép và dán một khối trong khi thiết kế luồng hội thoại.

Tính năng copy - paste khối hội thoại cho phép người dùng sao chép và dán một khối hội thoại bất kỳ trong phạm vi xây dựng kịch bản V2. Tính năng này nhằm giúp người dùng tiết kiệm thời gian tạo kịch bản và hoàn thiện kịch bản ở tốc độ nhanh hơn.

Tính năng sao chép và dán được áp dụng cho tất cả các khối hội thoại trên kịch bản V2.

![](../.gitbook/assets/15.png)
