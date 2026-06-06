# 📋 Personal Work Tracker (Ứng dụng Chấm Công Cá Nhân)

Một ứng dụng web nhỏ gọn, tối giản và bảo mật, giúp lập trình viên và người đi làm tự quản lý, theo dõi ngày công, giờ làm việc thực tế, tính toán thời gian tăng ca (OT) và lưu trữ lịch sử công việc hoàn toàn cục bộ (Local First).

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Tính năng nổi bật

- **Quản lý Chấm công Linh hoạt:** Hỗ trợ hai hình thức chính là `Đi làm (Work)` và `Nghỉ phép (Leave)` (Nghỉ phép hưởng lương mặc định tính 8 giờ công).
- **Tự động Tính toán Thời gian:**
  - Tự động trừ 1 giờ nghỉ trưa (`12:00 - 13:00`) nếu khung giờ làm việc đi qua khoảng thời gian này.
  - Tự động tính toán số giờ tăng ca (Overtime) một cách chính xác sau giờ hành chính (`17:00`).
- **Lịch Tra cứu Thông minh (Dynamic Calendar View):**
  - Giao diện trực quan hiển thị trạng thái từng ngày trong tháng (✓: Đi làm/Chủ Nhật, ✈️: Nghỉ phép, ×: Chưa chấm công).
  - Tích hợp bộ nút điều hướng độc lập (◀ Tháng trước / Tháng sau ▶) giúp dễ dàng kiểm tra dữ liệu quá khứ hoặc lên kế hoạch tương lai.
- **Bộ lọc Dữ liệu Cố định theo Tháng:** Số liệu tổng kết (Tổng ngày công, Tổng giờ làm, Tổng OT) được cô đọng và hiển thị chính xác theo tháng đang chọn mà không bị loãng thông tin bởi dữ liệu cũ.
- **Nhập liệu Nhanh (Quick Action):** Bấm trực tiếp vào một ngày bất kỳ trên Lịch để tự động điền thông tin hoặc chỉnh sửa nhanh bản ghi cũ.
- **Bảo mật và Riêng tư:** Dữ liệu lưu trữ 100% tại `LocalStorage` trên trình duyệt của người dùng. Không thu thập thông tin, không cần Server backend.
- **Xuất Dữ liệu:** Hỗ trợ xuất toàn bộ lịch sử chấm công ra file `.csv` (đã cấu hình sẵn UTF-8 BOM phòng lỗi font Excel) phục vụ báo cáo cuối tháng.

---

## 📸 Giao diện ứng dụng

Ứng dụng được thiết kế theo phong cách giao diện Clean UI của hệ điều hành iOS (Apple Style) với các bo góc mềm mại, hiển thị responsive mượt mà trên cả máy tính (Desktop) và điện thoại di động (Mobile).

---
