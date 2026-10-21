# 🤖 Phần 3 – Hỏi AI đúng cách và lưu tài liệu

## Prompt giải thích thuật ngữ API

### Tôi là ai / Bối cảnh

Tôi là sinh viên năm nhất ngành Công nghệ thông tin, chưa có nhiều kiến thức về lập trình. Tôi đang tham gia dự án SmartCampus, một ứng dụng di động giúp sinh viên tra cứu lịch học và phòng học trống.

### Chủ đề / Nội dung cần xử lý

Hãy giải thích thuật ngữ API (Application Programming Interface) và vai trò của API trong dự án SmartCampus.

### Yêu cầu

- Giải thích API bằng ngôn ngữ đơn giản, dễ hiểu với người mới học CNTT.
- Đưa ra ví dụ thực tế liên quan đến việc tra cứu lịch học trên SmartCampus.
- Trình bày cách API hoạt động theo các bước cơ bản.
- Nêu ví dụ về yêu cầu và dữ liệu phản hồi giữa ứng dụng và máy chủ.

### Không cần

- Không giải thích quá sâu về lập trình hoặc các giao thức phức tạp.
- Không sử dụng quá nhiều thuật ngữ tiếng Anh khó hiểu.

## Câu trả lời của AI

### Khái niệm API

**API (Application Programming Interface)** là giao diện cho phép các phần mềm giao tiếp và trao đổi dữ liệu với nhau.

Có thể hiểu API giống như **người phục vụ trong nhà hàng**: khách gọi món, người phục vụ chuyển yêu cầu đến nhà bếp rồi mang kết quả trở lại cho khách.

### Ví dụ API trong SmartCampus

Khi sinh viên muốn xem lịch học trên SmartCampus, ứng dụng cần lấy dữ liệu lịch học từ máy chủ của trường. API giúp ứng dụng gửi yêu cầu và nhận dữ liệu trả về.

### Cách API hoạt động

- **Gửi yêu cầu:** Ứng dụng gửi yêu cầu lấy lịch học thông qua API.
- **Xử lý:** Máy chủ nhận yêu cầu và tìm dữ liệu lịch học tương ứng.
- **Trả kết quả:** Máy chủ gửi dữ liệu về ứng dụng thông qua API.
- **Hiển thị:** Ứng dụng sử dụng dữ liệu nhận được để hiển thị lịch học cho sinh viên.

Ví dụ:
- Yêu cầu: Lấy lịch học của sinh viên có mã SV001.
- Phản hồi: Danh sách môn học, thời gian và phòng học tương ứng.

### Vai trò của API

- Giúp ứng dụng lấy dữ liệu từ máy chủ.
- Giúp các phần mềm giao tiếp với nhau theo quy tắc.
- Hỗ trợ SmartCampus lấy thông tin lịch học mà không cần lưu toàn bộ dữ liệu của trường trực tiếp trong ứng dụng.

### Kết luận

API là cầu nối giúp ứng dụng và máy chủ trao đổi dữ liệu. Trong SmartCampus, API có thể được sử dụng để lấy lịch học và các thông tin cần thiết cho sinh viên.

## Tóm tắt câu trả lời theo chiến lược đọc 3 bước

- **Scan Heading:** Xác định các phần khái niệm, ví dụ, cách hoạt động và vai trò của API.
- **Đọc phần chữ đậm:** Tập trung vào định nghĩa API và các bước gửi yêu cầu, xử lý, trả kết quả.
- **Xem Bullet List:** Nắm các chức năng chính của API trong dự án SmartCampus.

**Tóm tắt bằng lời của mình:**

API là cầu nối giúp các phần mềm giao tiếp và trao đổi dữ liệu với nhau. Trong SmartCampus, API giúp ứng dụng gửi yêu cầu đến máy chủ để lấy lịch học và hiển thị kết quả cho sinh viên. API giúp việc trao đổi dữ liệu giữa ứng dụng và máy chủ diễn ra theo quy tắc rõ ràng.

## Quy trình lưu file api_giai_thich.md

- **Bước 1:** Mở StackEdit và tạo một tài liệu Markdown mới.
- **Bước 2:** Sao chép toàn bộ câu trả lời AI ở phần trên và dán vào tài liệu mới.
- **Bước 3:** Kiểm tra tiêu đề, danh sách, chữ in đậm và nội dung hiển thị trong Preview.
- **Bước 4:** Xuất hoặc tải xuống tài liệu dưới định dạng Markdown và lưu tên file là `api_giai_thich.md`.

---

# 🐛 Phần 4 – Bẫy cú pháp

## Hai lỗi cú pháp

- **Lỗi 1 – Bảng thiếu dòng phân cách:** Bảng chưa có dòng `|---|---|` bên dưới hàng tiêu đề để phân cách tiêu đề và dữ liệu.
- **Lỗi 2 – Task List thiếu dấu cách:** Hai dòng `-[x]` và `-[ ]` thiếu một dấu cách sau dấu `-`. Cú pháp đúng là `- [x]` và `- [ ]`.

## Đoạn Markdown đã sửa

| Tính năng | Trạng thái |
|---|---|
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
