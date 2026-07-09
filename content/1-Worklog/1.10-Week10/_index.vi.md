---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Phát triển Lambda function `insights` phục vụ phân tích mẫu ứng tuyển và AI Chat.
* Phát triển Lambda function `settings` cho tính năng mục tiêu và streak ứng tuyển hàng tuần.
* Phát triển Lambda function `notes` cho tính năng ghi chú theo timeline từng job.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Phát triển Lambda function `insights`: nhận payload lịch sử ứng tuyển và gọi API Bedrock. | 22/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 2 | Triển khai streaming response từ Bedrock cho tính năng AI Chat trong `insights`. | 24/06/2026 | 25/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Triển khai logic phân tích pattern (tỉ lệ phản hồi theo phiên bản CV, theo kênh ứng tuyển) trong `insights`. | 25/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 4 | Phát triển Lambda function `settings` để lưu và cập nhật mục tiêu, streak ứng tuyển hàng tuần. | 26/06/2026 | 27/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 5 | Phát triển Lambda function `notes` với đầy đủ thao tác CRUD cho ghi chú theo timeline từng job. | 27/06/2026 | 28/06/2026 | https://docs.aws.amazon.com/lambda/ |

### Kết quả đạt được tuần 10:

* Hoàn thành **Lambda function `insights`**, nhận lịch sử ứng tuyển của người dùng và gọi **Amazon Bedrock** để sinh phản hồi AI Chat và phân tích pattern (ví dụ phiên bản CV hoặc kênh nào hiệu quả nhất).

* Triển khai **streaming text** từ Bedrock để tính năng AI Chat phản hồi dần thay vì phải chờ toàn bộ kết quả.

* Hoàn thành **Lambda function `settings`**, xử lý mục tiêu ứng tuyển và streak hàng tuần cho từng người dùng.

* Hoàn thành **Lambda function `notes`**, hỗ trợ đầy đủ CRUD cho ghi chú gắn theo timeline của từng đơn ứng tuyển.

### Kế hoạch tuần tiếp theo:

* Phát triển Lambda function `digest`: tổng hợp dữ liệu tuần, gọi Bedrock tạo tóm tắt và gửi qua SES.

* Phát triển Lambda function `followup`: cron job hàng ngày nhắc người dùng về các deadline ứng tuyển sắp tới.

* Bắt đầu viết Unit/Integration test bằng pytest và moto (mock AWS).
