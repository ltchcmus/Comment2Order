# Comment2Order - Chuyển Tin Nhắn Thành Đơn Hàng

## Giới thiệu

Comment2Order là một ứng dụng dành cho home baker và các cửa hàng nhỏ nhận đơn hàng qua tin nhắn.

Dự án hướng đến việc giải quyết những khó khăn thường gặp khi chủ cửa hàng phải đọc và xử lý thủ công nhiều tin nhắn đặt hàng, chẳng hạn như:

- Thông tin món hàng và số lượng được viết theo nhiều cách khác nhau.
- Thời gian nhận hàng có thể nằm xen kẽ trong nội dung tin nhắn.
- Các ghi chú hoặc thông tin dị ứng dễ bị bỏ sót.
- Chủ cửa hàng phải tự tổng hợp lại nội dung trước khi xác nhận đơn hàng.

## Ý tưởng hoạt động

Khách hàng có thể gửi tin nhắn đặt hàng bằng ngôn ngữ tự nhiên, ví dụ:

> 2 box croissant, pick up Saturday 3pm, no nuts

Comment2Order sẽ sử dụng mô hình ngôn ngữ lớn (LLM) để phân tích tin nhắn và chuyển nội dung thành một bản nháp đơn hàng có cấu trúc, bao gồm:

- Món hàng.
- Số lượng.
- Thời gian nhận hàng.
- Ghi chú.
- Thông tin dị ứng.

Bản nháp này không được tự động xác nhận. Chủ cửa hàng hoặc nhân viên cần kiểm tra, chỉnh sửa nếu cần và phê duyệt trước khi đơn hàng được xác nhận chính thức.

## Thành viên nhóm

| MSSV | Họ và tên |
| --- | --- |
| 23120200 | Nguyễn Hưng Thịnh |
| 23120222 | Lê Thành Công |
| 23120252 | Nguyễn Phúc Hậu |
