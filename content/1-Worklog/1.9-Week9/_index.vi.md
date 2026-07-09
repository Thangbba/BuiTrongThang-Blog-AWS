---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Khởi động đồ án nhóm SmartCV (hệ thống theo dõi đơn xin việc ứng dụng AI) cùng nhóm TechTitans.
* Nghiên cứu Amazon Bedrock và chọn model phù hợp cho tính năng AI coaching.
* Thiết kế luồng Prompt Engineering cho tính năng phân tích mẫu CV/đơn ứng tuyển.
* Thiết kế logic Cron Job bằng AWS EventBridge cho tính năng gửi email báo cáo tuần.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Cùng nhóm chốt đề tài SmartCV và định hướng công nghệ Serverless. | 15/06/2026 | 15/06/2026 | https://aws.amazon.com/vi/serverless/ |
| 2 | Nghiên cứu API Amazon Bedrock và các model nền tảng hiện có. | 16/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Đánh giá và chọn model Amazon Nova Lite, tối ưu chi phí và hỗ trợ region ap-southeast-1. | 18/06/2026 | 18/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 4 | Thiết kế luồng tương tác Prompt Engineering cho tính năng phân tích CV/đơn ứng tuyển. | 19/06/2026 | 20/06/2026 | https://docs.aws.amazon.com/bedrock/ |
| 5 | Thiết kế logic Cron Job bằng AWS EventBridge cho tính năng gửi email tổng kết hàng tuần. | 20/06/2026 | 21/06/2026 | https://docs.aws.amazon.com/eventbridge/ |

### Kết quả đạt được tuần 9:

* Cùng nhóm chốt được phạm vi dự án **SmartCV** và định hướng kiến trúc Serverless tổng thể.

* Nghiên cứu **Amazon Bedrock** và chọn được model **Amazon Nova Lite** phù hợp nhất về chi phí và khả năng triển khai theo vùng.

* Thiết kế xong luồng **Prompt Engineering** để đưa dữ liệu ứng tuyển vào Bedrock, phục vụ tính năng AI coaching cá nhân hóa.

* Thiết kế xong logic **Cron Job bằng EventBridge**, làm nền tảng cho tính năng gửi email tổng kết hàng tuần sau này.

### Kế hoạch tuần tiếp theo:

* Bắt đầu code Lambda function `insights`: nhận payload lịch sử ứng tuyển và gọi API Bedrock để phân tích mẫu và AI Chat.

* Code Lambda function `settings` (mục tiêu ứng tuyển/streak hàng tuần) và Lambda function `notes` (CRUD ghi chú theo timeline từng job).
