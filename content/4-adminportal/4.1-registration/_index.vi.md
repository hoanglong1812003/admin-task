---
title: "4.1. Registration"
weight: 1
---

Trang Registration là nơi quản lý toàn bộ thông tin đăng ký của người dùng trong hệ thống. Trang này cung cấp các tính năng xem, tìm kiếm, lọc và quản lý các đơn đăng ký.

#### Tổng quan trang Đăng nhập

- Giao diện trang đăng nhập

![Registration Overview](/images/admin/4.1-registration/15.png)

#### Trang Dashboard

![Search and Filter](/images/admin/4.1-registration/16.png)

#### Trang Pending Approvals

- Tại trang này hiển thị:
    - Số lượng sinh viên đăng ký lên văn phòng, 
    - Số lượng sinh viên được duyệt
    - Số lượng sinh viên bị từ chối

![View Details](/images/admin/4.1-registration/17.png)

- Khi click vào một ngày đăng ký, chúng ta có thể xem thông tin và trạng thái của từng sinh viên.
- Ví dụ ở đây chọn trạng thái **Pending**, hiển thị **500** bạn sinh viên.

![Additional Details](/images/admin/4.1-registration/18.png)

- Chọn một bạn sinh viên và bấm **Approved** để duyệt lên văn phòng.

![Approval Process](/images/admin/4.1-registration/19.png)

#### Trang Check-in / Check-out

- Trang này hiển thị các bạn sinh viên đã check-in, chờ check-in hoặc vắng.

![Approval Confirmation](/images/admin/4.1-registration/20.png)

- Chọn một ngày và lọc theo **Absent** để xem sinh viên vắng ngày hôm đó.

![Edit Registration](/images/admin/4.1-registration/21.png)

#### Floor config

- Đây là trang mở khóa lịch cho các bạn sinh viên đăng ký lên văn phòng.

![Edit Form](/images/admin/4.1-registration/22.png)

- Sau khi hoàn thành việc book phòng với bên chị Thu.
- Tiến hành chọn ngày trống và mở khóa tầng 26 cho các bạn sinh viên đăng ký.

![Bulk Actions](/images/admin/4.1-registration/23.png)

#### Floors

- Trang này hiển thị số lượng được phép đăng ký ở tầng 26

![Bulk Confirmation](/images/admin/4.1-registration/24.png)

- Chọn điều chỉnh để tăng số lượng **pending** lên 600.

![Advanced Filter](/images/admin/4.1-registration/25.png)

#### Shifts

- Điều chỉnh thời gian sinh viên đăng ký lên văn phòng.
- Mặc định sẽ là từ **09hh00 - 17h00**.

![Filter Results](/images/admin/4.1-registration/26.png)

#### Schedule

- Điều chỉnh thời gian mở lịch đăng ký của các ngày trong tuần.
- Mặc định sẽ mở từ **09hh - 17h00** tại các ngày trong tuần.

![Document Management](/images/admin/4.1-registration/27.png)

#### Attdendance

- Hiển thị thời gian check-in cho các bạn sinh viên.
- Mặc định sẽ là từ **08h30 - 09h00**, **sau 09h30** sinh viên check-in sẽ được coi là đi trễ.
- Chúng ta có thể điều chỉnh thời gian bao lâu mới là trễ dành cho các bạn sinh viên. Thông thường **sau 30 phút** sẽ là trễ.

![Document Preview](/images/admin/4.1-registration/28.png)

- Hiển thị thời gian các bạn sinh viên có thể check-out.
- Mặc định sẽ là từ **16h00 - 17h00**. 
- Tùy theo trường hợp mà điều chỉnh thời gian để các bạn sinh viên có thể check-out sớm.

![Change History](/images/admin/4.1-registration/29.png)

#### Auto Approval

- **HÃY CẨN THẬN VỚI TRANG NÀY**
- **HÃY CẨN THẬN VỚI TRANG NÀY**
- **HÃY CẨN THẬN VỚI TRANG NÀY**
- Đây là trang sẽ duyệt tự động các bạn sinh viên đăng ký.
- Bật **Enable Auto-Approval** và ấn **Save** để kích hoạt.

![Statistics](/images/admin/4.1-registration/30.png)

- Sau đó chọn phương thức duyệt.
- Mặc định sẽ chọn **Fair by Approved Count**

![Reports](/images/admin/4.1-registration/31.png)

- Điều chỉnh số lượng duyệt. Thông thường sẽ là 100.
- **Sau 16h00**, hệ thống sẽ tiến hành duyệt random các bạn sinh viên.

![Settings](/images/admin/4.1-registration/32.png)

**Lưu ý quan trọng:**
- Luôn kiểm tra kỹ thông tin trước khi duyệt
- Đảm bảo các bạn sinh viên ít buổi sẽ được ưu tiên duyệt.
- Sau khi quá trình tự động duyệt hoàn tất, quay lại trang **Pending Approval** để kiểm tra số lượng
- Đồng thời truy cập [Email logs](https://hcm-admin.awsfcaj.com/email/logs) để kiểm tra email đã được gửi thành công đến các bạn sinh viên đã được duyệt chưa.
