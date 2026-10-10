---
title: Chính sách quyền riêng tư
---

# Chính sách quyền riêng tư

**Ứng dụng:** Media-Management-HITL  
**Ngày cập nhật:** 10/10/2026

Media-Management-HITL hỗ trợ tạo nội dung bằng AI, kiểm duyệt bởi con người và xuất bản lên website hoặc Fanpage Facebook được người quản trị cho phép.

## 1. Dữ liệu Facebook được sử dụng

Hệ thống sử dụng các dữ liệu cần thiết để kết nối và đăng bài:

- ID và tên Fanpage.
- Page Access Token để xác thực yêu cầu với Facebook.
- Nội dung bài viết được chọn để xuất bản.
- ID bài đăng, trạng thái xuất bản và thông báo lỗi từ Facebook.

Trong quá trình thiết lập kết nối, User Access Token có thể được sử dụng để lấy danh sách Fanpage mà người dùng có quyền quản lý.

Chức năng hiện tại không thu thập tin nhắn riêng tư, danh sách bạn bè hoặc thông tin khách hàng từ Facebook.

## 2. Mục đích sử dụng

Dữ liệu được sử dụng để:

- Xác định và kết nối đúng Fanpage.
- Xác thực yêu cầu đăng bài.
- Xuất bản nội dung đã được phê duyệt.
- Theo dõi kết quả và xử lý lỗi xuất bản.

AI tạo bản nháp. Người kiểm duyệt kiểm tra, chỉnh sửa, phê duyệt hoặc từ chối trước khi hệ thống xuất bản theo cấu hình.

## 3. Lưu trữ và bảo vệ dữ liệu

Nội dung bài viết, lịch sử kiểm duyệt và kết quả xuất bản được lưu trong MongoDB của hệ thống. Workflow chạy bằng n8n trên máy chủ hoặc máy ảo do nhóm quản trị quản lý.

Thông tin kết nối Facebook được cấu hình phía máy chủ bằng biến môi trường hoặc credentials của n8n. Access token không được đưa vào nội dung bài đăng hoặc trang công khai.

Ứng dụng phân quyền cho tài khoản quản trị và người kiểm duyệt. Người vận hành chịu trách nhiệm bảo vệ máy chủ, thông tin cấu hình và bản sao lưu.

## 4. Dịch vụ bên ngoài

Khi đăng bài, hệ thống gửi nội dung và thông tin xác thực cần thiết đến Meta.

Khi tạo nội dung bằng Gemini hoặc dịch vụ AI khác, brief và nội dung cần xử lý được gửi đến nhà cung cấp AI tương ứng. Access token Facebook không được sử dụng làm đầu vào cho AI.

Hệ thống không bán dữ liệu Facebook cho bên thứ ba.

## 5. Thời gian lưu trữ

Dữ liệu được lưu trong thời gian cần thiết để vận hành, kiểm duyệt và đối chiếu kết quả, hoặc cho đến khi có yêu cầu xóa hợp lệ.

Token được thay thế hoặc gỡ khỏi cấu hình khi cập nhật hoặc chấm dứt kết nối. Dữ liệu trong bản sao lưu có thể tồn tại đến khi bản sao lưu được thay thế hoặc xóa.

## 6. Yêu cầu xóa dữ liệu

Gửi yêu cầu đến **bieen1006@gmail.com** với tiêu đề:

**Yêu cầu xóa dữ liệu — Media-Management-HITL**

Vui lòng cung cấp:

- ID hoặc đường dẫn Fanpage.
- Email để nhận phản hồi.
- Phạm vi dữ liệu muốn xóa.

**Không gửi mật khẩu hoặc access token qua email.**

Sau khi xác minh quyền của người yêu cầu, nhóm quản trị sẽ ngừng sử dụng kết nối, gỡ token và xóa dữ liệu liên quan trong phạm vi hệ thống quản lý; đồng thời thông báo kết quả hoặc giới hạn xử lý.

Xóa dữ liệu trong hệ thống không tự động xóa bài đã đăng trên Facebook. Người quản trị Fanpage có thể xóa các bài đó trực tiếp trên Facebook và thu hồi quyền truy cập của ứng dụng trong phần cài đặt tương ứng.

## 7. Liên hệ

Mọi câu hỏi và yêu cầu liên quan đến dữ liệu vui lòng gửi đến:

**Email: [bieen1006@gmail.com]**

Chính sách sẽ được cập nhật khi chức năng hoặc phạm vi xử lý dữ liệu thay đổi.
