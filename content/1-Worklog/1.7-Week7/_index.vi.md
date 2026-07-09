---
title: "Worklog Tuần 7"
date: 2026-05-25
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Triển khai website tĩnh trên Amazon S3, tăng tốc bằng Amazon CloudFront.
* Triển khai AWS Backup với Backup Plan, Vault và kiểm thử Restore.
* Thực hành Import/Export máy ảo giữa môi trường On-premises và AWS.
* Thực hành với IAM Role được các dịch vụ AWS sử dụng.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Tạo S3 Bucket, tải website tĩnh lên và bật Static Website Hosting. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | Cấu hình Amazon CloudFront đứng trước S3 Bucket và chặn truy cập public trực tiếp vào bucket. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | Tạo AWS Backup Vault và Backup Plan, chạy và kiểm thử Restore, cấu hình thông báo qua SNS. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | Thực hành xuất máy ảo từ EC2 Instance/AMI và nhập máy ảo từ máy chủ cục bộ vào AWS. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | Tạo và cấu hình IAM Role (vmimport), xem lại các IAM Policy cần thiết cho quy trình VM Import/Export. | 25/05/2026 | 25/05/2026 | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 7:

* Triển khai thành công **website tĩnh trên Amazon S3**, tăng tốc và bảo mật bằng **Amazon CloudFront**, chặn truy cập public trực tiếp vào bucket.

* Triển khai và kiểm thử **AWS Backup**, gồm Backup Plan, Backup Vault và Restore đã được xác nhận, cùng thông báo trạng thái qua **Amazon SNS**.

* Thực hành trọn vẹn quy trình **VM Import/Export** — xuất máy ảo từ EC2 Instance/AMI và nhập máy ảo cục bộ vào AWS.

* Cấu hình **IAM Role và Policy (vmimport)** cần thiết để hỗ trợ dịch vụ VM Import/Export.

### Kế hoạch tuần tiếp theo:

* Hoàn tất các Lab lưu trữ còn lại (AWS Storage Gateway) và bắt đầu tổng hợp ghi chú cho báo cáo thực tập và buổi thuyết trình cuối kỳ.
