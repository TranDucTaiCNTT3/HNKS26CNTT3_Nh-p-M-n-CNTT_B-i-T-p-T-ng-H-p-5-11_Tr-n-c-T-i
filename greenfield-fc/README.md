# GreenField FC – Quản lý đội bóng

Chào mừng bạn đến với dự án **quản lý đội bóng** của *câu lạc bộ* GreenField FC. Đây là giải pháp toàn diện giúp tối ưu hóa việc quản lý lịch thi đấu, danh sách cầu thủ cũng như thống kê hiệu suất. Dự án ban đầu vốn chỉ là một ~~bản nháp~~ nhỏ nhưng nay đã được phát triển thành hệ thống hoàn chỉnh. Bạn có thể mở giao diện chính thông qua tệp `web/index.html`.

![GreenField FC Logo](web/images/greenfield-logo.png)

---

## Cấu trúc thư mục và Cài đặt

### Các thư mục chính

| Thư mục | Nội dung |
| :--- | :--- |
| `docs` | Tài liệu bàn giao |
| `data` | Danh sách cầu thủ và trận đấu |
| `logs` | Log website |

### Hướng dẫn thiết lập

1. Cập nhật mã nguồn và các gói phụ thuộc.
   - Chạy lệnh `npm install` để cài đặt thư viện.
   - Kiểm tra tệp cấu hình `config.json`.
2. Khởi tạo dữ liệu ban đầu cho hệ thống.
3. Chạy ứng dụng và kiểm tra đường dẫn [Trang chủ Web](web/index.html).

---

## Hướng dẫn sử dụng và Lệnh

### Danh sách tính năng

- Quản lý thông tin cầu thủ
  - Theo dõi danh sách chấn thương
  - Ghi nhận chỉ số thể lực
- Lịch thi đấu và kết quả
- Báo cáo thống kê tài chính

### Lệnh kiểm tra tệp tin

```bash
ls -Recurse
```

### Task List

- [x] Sắp xếp thư mục dự án
- [ ] Đưa dự án lên GitHub

### Lưu ý

> Không tải file `.env` lên GitHub.
>
>  Hãy luôn kiểm tra kỹ tệp `.gitignore` trước khi thực hiện commit.
