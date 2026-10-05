Hello from main and feature



## Báo cáo bài 2: Quản lý nhánh và Merge Conflict

- Khởi tạo Git và tạo file `README.md`.
- Tạo nhánh `feature-update` và chỉnh sửa nội dung `README.md`, sau đó commit.
- Quay lại nhánh `main`, chỉnh sửa cùng dòng trong `README.md` với nội dung khác và commit.
- Thực hiện `git merge --no-ff feature-update`.
- Git xuất hiện xung đột với các ký hiệu `<<<<<<<`, `=======`, `>>>>>>>`.
- Mở file `README.md`, xóa các ký hiệu xung đột và chỉnh sửa lại nội dung thủ công.
- Chạy `git add README.md` và commit để hoàn tất merge.
- Kiểm tra lịch sử bằng lệnh:

`git log --graph --oneline`

Kết quả: Nhánh `feature-update` đã được gộp vào `main` thành công và có merge commit.
