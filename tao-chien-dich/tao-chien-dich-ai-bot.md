# Tạo chiến dịch AI BOT

Chỉ 4 bước để bắt đầu một chiến dịch gọi hàng loạt cho AI BOT

* B1: Tạo mới chiến dịch
* B2: Cài đặt kịch bản
* B3: Thêm danh sách khách hàng
* B4: Cài đặt nâng cao, thiết lập tham số mã cuộc gọi

Xem báo cáo tự động tại 5. Báo cáo

## Tạo mới chiến dịch&#x20;

(1) Chọn tab "Chiến dịch"

(2) Chọn "Tạo mới"

(3) Nhập Tên chiến dịch và mã chiến dịch&#x20;

(4) Chọn "Kịch bản thoại"&#x20;

(5) Chọn "Bắt đầu chiến dịch" để sang bước "Cài đặt kịch bản"

![Tạo chiến dịch gọi mới ](<../.gitbook/assets/image (45).png>)

## Cài đặt kịch bản&#x20;

![](<../.gitbook/assets/image (35).png>)

(1) Chọn giọng trợ lý ảo.

(2) Mã kết quả (Action code)

Mã kết quả được Voicebot AI ghi nhận sau khi kết thúc cuộc gọi. Cài đặt kết quả tương ứng với trạng thái cuộc gọi theo ghi chú sau. &#x20;

<table><thead><tr><th width="270.9868627455859">Trạng thái cuộc gọi</th><th width="216.03530640214058">Trạng thái cuộc gọi</th><th>Mã kết quả</th></tr></thead><tbody><tr><td>USER_HANGUP</td><td>KH cúp máy</td><td><p>{code} </p><p><span data-gb-custom-inline data-tag="emoji" data-code="26a0">⚠️</span> <em>Mã trả về là mã cuộc gọi được cài đặt ở kịch bản.</em></p></td></tr><tr><td>BOT_HANGUP</td><td>Bot cúp máy</td><td><p>{code} </p><p><span data-gb-custom-inline data-tag="emoji" data-code="26a0">⚠️</span> <em>Mã trả về là mã cuộc gọi được cài đặt ở kịch bản.</em></p></td></tr><tr><td>BUSY</td><td>Máy bận</td><td>BS</td></tr><tr><td>NOANSWER</td><td>KH không bắt máy</td><td>NA</td></tr><tr><td>SHORT_CALL</td><td>Cuộc gọi ngắn (nhỏ hơn 5s)</td><td>SC</td></tr><tr><td>AGENT_NOT_PICK_UP</td><td>ĐTV không bắt máy</td><td>ANP</td></tr><tr><td>DIAL_HANGUP </td><td>ĐTV cúp máy</td><td>AHU </td></tr><tr><td>CHANNEL_UNAVAILABLE</td><td>Kênh không khả dụng</td><td>CU</td></tr></tbody></table>

{% hint style="info" %}
Mã kết quả được thiết lập sẵn trong trường hợp sử dụng voicebot AI dựng sẵn.
{% endhint %}



(3) Chọn "Tiếp tục" để đến bước "Thêm danh sách khách hàng".&#x20;

## Thêm danh sách khách hàng

![Tải lên danh sách khách hàng](<../.gitbook/assets/image (43).png>)

(1) Chọn "Tải lên danh sách gọi"

(2) Chọn File để tải lên danh sách có sẵn&#x20;

{% hint style="info" %}
Chọn "Tải xuống" mẫu danh sách khách hàng&#x20;
{% endhint %}

![Mẫu danh sách khách hàng tải lên AI BOT](<../.gitbook/assets/image (9).png>)

(3) "Tải lên" danh sách gọi

{% hint style="info" %}
Sau khi tải lên có thể chỉnh sửa hoặc xóa liên hệ
{% endhint %}

![Danh sách gọi sau khi tải lên](<../.gitbook/assets/image (3).png>)

(4) Chọn "Tiếp tục" để đến "Cài đặt nâng cao"

## Cài đặt nâng cao

(1) Điền email nhận báo cáo sau khi chiến dịch kết thúc

(2) Chọn thời gian chiến dịch

* Ngày bắt đầu - kết thúc chiến dịch&#x20;
* Khoảng thời gian bắt đầu chiến dịch (Có thể thiết lập nhiều khung giờ trong ngày)

(3) Cài đặt điều kiện AI BOT tự động gọi lại cho khách hàng&#x20;

* 1\) Chọn **"+Thêm điều kiện"**&#x20;
* 2\) Tích chọn một hoặc nhiều điều kiện gọi lại tại mục hiển thị
  * Máy bận: Gọi lại khi đường truyền bận&#x20;
  * Không trả lời: Gọi lại khi khách hàng không bắt máy
  * Không thể kết nối: Gọi lại khi đường truyền lỗi
  * Action Code (Mã kết quả) : Gọi lại tuỳ theo mã kết quả cuộc gọi

![Cài đặt nâng cao cho chiến dịch ](<../.gitbook/assets/Chiendich-dieu kien goi lai.png>)

<figure><img src="../.gitbook/assets/Chiendich-dieu kien goi lai 1.png" alt=""><figcaption><p>Hướng dẫn cài đặt điều kiện gọi lại</p></figcaption></figure>

(4) Nhấn “Tiếp tục” để đến bước chạy chiến dịch và báo cáo

## Chạy chiến dịch

Tại mục 5. Báo cáo chọn “Chạy” để bắt đầu chiến dịch

![](<../.gitbook/assets/image (15).png>)
