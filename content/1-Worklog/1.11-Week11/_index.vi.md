---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Phát triển Lambda function `digest` cho tính năng gửi email tổng kết tuần tự động bằng Bedrock.
* Phát triển Lambda function `followup` nhắc nhở deadline ứng tuyển hàng ngày.
* Bắt đầu xây dựng bộ kiểm thử tự động bằng pytest và moto.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Phát triển Lambda function `digest`: tổng hợp dữ liệu ứng tuyển trong tuần của người dùng. | 29/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/lambda/ |
| 2 | Tích hợp Bedrock vào `digest` để sinh bản tóm tắt tuần và gợi ý cá nhân hóa. | 30/06/2026 | 01/07/2026 | https://docs.aws.amazon.com/bedrock/ |
| 3 | Kết nối `digest` với Amazon SES để gửi email tổng kết tuần vào mỗi sáng Thứ Hai. | 01/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/ses/ |
| 4 | Phát triển Lambda function `followup`: cron job hàng ngày quét các deadline ứng tuyển sắp đến/quá hạn và gửi email nhắc nhở qua SES. | 02/07/2026 | 03/07/2026 | https://docs.aws.amazon.com/lambda/ |
| 5 | Thiết lập môi trường test với pytest và moto, bắt đầu viết Unit/Integration test cho các Lambda function đã xây dựng. | 03/07/2026 | 05/07/2026 | https://docs.getmoto.org/ |

### Kết quả đạt được tuần 11:

* Hoàn thành **Lambda function `digest`**, tổng hợp hoạt động ứng tuyển hàng tuần của người dùng, gọi **Amazon Bedrock** để sinh tóm tắt và gợi ý, sau đó tự động gửi qua **Amazon SES** vào mỗi sáng Thứ Hai.

* Hoàn thành **Lambda function `followup`**, cron job hàng ngày nhắc người dùng về các đơn ứng tuyển sắp đến hoặc đã quá hạn follow-up.

* Thiết lập xong môi trường kiểm thử tự động với **pytest** và **moto** (mock dịch vụ AWS), viết đợt Unit/Integration test đầu tiên cho các Lambda function đã xây dựng trong Tuần 9–11.

### Kế hoạch tuần tiếp theo:

* Tối ưu hóa Prompt hệ thống (system prompt) của Bedrock để AI trả lời gãy gọn, đúng định dạng Markdown.

* Mở rộng bộ test để đạt mục tiêu hơn 200 test case với coverage ≥ 90%.

* Viết phần báo cáo về Tích hợp AI (Amazon Bedrock) và Chiến lược Integration/Unit Testing.
