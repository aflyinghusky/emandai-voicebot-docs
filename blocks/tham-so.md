# Tham số

Tham số được sử dụng để thu thập thông tin từ khách hàng thông qua chuỗi câu hỏi hoặc gán giá trị cụ thể theo điều kiện giúp AI BOT đưa ra phản hồi phù hợp theo ngữ cảnh hội thoại.&#x20;

**Ví dụ:** Tên, Số điện thoại, Email, Địa chỉ, Số lượng,...

## Lấy tham số <a href="#wlb5uenpqzl3" id="wlb5uenpqzl3"></a>

Sử dụng khối này khi cần tạo tham số lấy và lưu dữ liệu đầu vào từ khách hàng.

**Cách thiết lập**

(1) Kéo thả khối Lấy tham số vào canvas

(2) Nhấn chọn vào ô “tham số” để hiển thị giao diện cấu hình.

![](../.gitbook/assets/9)

(3) Thiết lập lấy tham số tại giao diện hiển thị

* Nhập tên tham số và chọn loại thực thể của tham số \[1]
* Nhập nội dung AI BOT phản hồi để thu thập tham số \[2]
* Trong trường hợp tham số cần lấy là “bắt buộc” phải có đồng nghĩa AI BOT chỉ tiếp tục hội thoại khi đã lấy được tham số. Kích chọn “Bắt buộc” \[3] và tiếp tục thiết lập các mục sau:
  * _Nhắc lại (lần) \[4]:_ Số lần mà AI BOT sẽ lặp lại lời nhắc \[5]
  * _Bot hỏi lại \[5]:_ Nếu sau phản hồi \[2] , USER vẫn chưa cung cấp tham số AI BOT sẽ phản hồi lời nhắc \[5]
* Chọn Lưu để hoàn tất thiết lập

![Thiết lập lấy tham số](../.gitbook/assets/10)



(4) Tạo kết nối từ tham số vừa tạo đến ý định / điều kiện / khối hành động tương ứng

_<mark style="color:red;">=> Trong trường hợp cần nhiều hơn 1 tham số để thực hiện bước tiếp theo, thiết lập như sau:</mark>_

(1) Kéo thả khối Tạo tham số vào Canvas

(2) Tạo các tham số cần AI BOT thu thập, ở ví dụ dưới tham số cần thu thập là “kích cỡ, màu sắc”

(3) Chọn tạo kết nối tại điểm _**“Khi tất cả tham số đều thỏa mãn”**_ (When all parameters are met) đến khối phản hồi AI BOT / ý định / điều kiện / khối hành động tương ứng.

![](../.gitbook/assets/11)

## Gán tham số <a href="#m0oye661f4uq" id="m0oye661f4uq"></a>

Sử dụng khối này để gán giá trị theo điều kiện cho tham số và sử dụng nó trong các phản hồi khác nhau của AI BOT

**Cách thiết lập**

(1) Kéo thả khối Gán tham số vào Canvas

(2) Nhập tên tham số và giá trị gán cho tham số đó

(3) Chọn Thêm để thêm tham số mới

![](../.gitbook/assets/12)

{% hint style="info" %}
Để thiết lập điều kiện gán tham số, kéo thả khối “Điều kiện” vào canvas và thiết lập theo hướng dẫn ở mục “[Điều kiện](khac.md#\_4tgmcablivlo)”&#x20;
{% endhint %}

## Nhãn

Sử dụng khối này để tạo nhãn / xóa nhãn phân loại đối tượng hoặc tạo các mã hành động tương ứng với ý định (ACTION CODE).

**Cách thiết lập**

(1) Kéo thả khối Nhãn vào Canvas \[1]

(2) Nhập giá trị nhãn và nhấn enter để lưu \[2]

(3) Tạo kết nối với ý định USER tương ứng muốn tạo nhãn phân loại \[3]

**Ví dụ**

* Ý định dong\_y\_mua tương ứng với nhãn da\_mua
* Ý định tu\_choi\_mua tương ứng với nhãn khong\_mua

{% hint style="info" %}
Nhãn có thể gán bằng tiếng việt. Ví dụ:  "có nhu cầu", "khách vip" ...
{% endhint %}

![](../.gitbook/assets/13)

### &#x20;<a href="#id-6hyc90yu3tpv" id="id-6hyc90yu3tpv"></a>
