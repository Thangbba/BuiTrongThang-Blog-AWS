---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Tối ưu hóa Prompt AI của Bedrock để phản hồi nhất quán, đúng định dạng.
* Đẩy bộ kiểm thử tự động đạt mục tiêu cuối cùng của dự án (hơn 200 test case, coverage ≥ 90%).
* Viết phần Tích hợp AI và Chiến lược kiểm thử cho báo cáo cuối kỳ.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Viết lại và tinh chỉnh Prompt hệ thống của Bedrock để phản hồi gãy gọn, đúng định dạng Markdown. | 06/07/2026 | 07/07/2026 | https://docs.aws.amazon.com/bedrock/ |
| 2 | Bổ sung test cho các trường hợp biên (input không hợp lệ, lịch sử rỗng, lỗi Bedrock/SES) vào bộ test. | 07/07/2026 | 08/07/2026 | https://docs.pytest.org/ |
| 3 | Đạt mốc kiểm thử của dự án: 207 test case cho Backend, coverage ≥ 90%. | 08/07/2026 | 09/07/2026 | https://docs.getmoto.org/ |
| 4 | Viết phần "Tích hợp AI (Amazon Bedrock)" cho báo cáo dự án. | 09/07/2026 | 09/07/2026 | — |
| 5 | Viết phần "Chiến lược Integration/Unit Testing" cho báo cáo dự án. | 09/07/2026 | 10/07/2026 | — |

### Kết quả đạt được tuần 12:

* Hoàn thiện **Prompt hệ thống của Bedrock**, đảm bảo tính năng AI Chat và digest luôn trả về phản hồi gãy gọn, đúng cấu trúc Markdown.

* Đạt mốc kiểm thử của nhóm: **207 test case cho Backend với coverage ≥ 90%**, bao phủ các Lambda function `insights`, `settings`, `notes`, `digest` và `followup`.

* Hoàn thành các phần báo cáo được phân công: **Tích hợp AI (Amazon Bedrock)** và **Chiến lược Integration/Unit Testing**.

### Kế hoạch tuần tiếp theo:

* Đây là tuần cuối của chương trình thực tập — tập trung rà soát toàn bộ báo cáo, hoàn thiện tài liệu dự án SmartCV và chuẩn bị cho buổi thuyết trình/demo cuối kỳ.
