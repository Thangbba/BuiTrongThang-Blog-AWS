---
title: "Worklog Tuần 5"
date: 2026-05-11
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Áp dụng lý thuyết mạng của Module 02 vào thực hành các bài Lab.
* Triển khai VPC Peering, AWS Transit Gateway và Hybrid DNS với Route 53 Resolver.
* Triển khai Lab AWS Site-to-Site VPN và xử lý sự cố kết nối bằng Reachability Analyzer.
* Ôn lại AWS Budgets, thực hành tạo nhiều loại Budget khác nhau để quản trị chi phí.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Triển khai Lab VPC Peering: tạo hai VPC, cấu hình Route Table và kiểm tra Cross-Peer DNS Resolution. | 11/05/2026 | 11/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | Triển khai AWS Transit Gateway với Attachment và Route Propagation để tập trung định tuyến cho nhiều VPC. | 11/05/2026 | 12/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | Triển khai Lab Hybrid DNS bằng Route 53 Resolver: tạo Inbound/Outbound Endpoint, Resolver Rules và AWS Managed Microsoft AD, kiểm tra bằng nslookup. | 12/05/2026 | 13/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | Triển khai Lab Amazon VPC và AWS Site-to-Site VPN Workshop, bao gồm EC2, Security Group và Network ACL. | 14/05/2026 | 15/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 5 | Dùng Reachability Analyzer để xử lý sự cố kết nối, thực hành tạo các loại Budget: Cost, Usage, Reserved Instance và Savings Plan trong AWS Budgets. | 16/05/2026 | 17/05/2026 | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 5:

* Triển khai và kiểm tra thành công kết nối **VPC Peering** giữa hai VPC, xác nhận kết nối qua Private IP và Cross-Peer DNS Resolution.

* Triển khai **AWS Transit Gateway** với Attachment và Route Propagation, đơn giản hóa định tuyến cho nhiều VPC.

* Hoàn thành Lab **Hybrid DNS với Route 53 Resolver**, gồm Inbound/Outbound Endpoint, Resolver Rules và AWS Managed Microsoft AD, xác nhận phân giải DNS hai chiều bằng nslookup.

* Triển khai đầy đủ môi trường **Amazon VPC và Site-to-Site VPN**, gồm Subnet, Internet Gateway, NAT Gateway và Security Group.

* Thực hành dùng **Reachability Analyzer** để chẩn đoán sự cố mạng liên quan đến ENI, Security Group và Network ACL.

* Tạo nhiều loại **AWS Budgets** (Cost, Usage, Reserved Instance, Savings Plan) để nâng cao kỹ năng quản trị chi phí.

### Kế hoạch tuần tiếp theo:

* Dọn dẹp các tài nguyên mạng đã triển khai trong tuần để kiểm soát chi phí.

* Chuyển hướng sang Module 03/04, tìm hiểu các dịch vụ lưu trữ AWS (Amazon S3, CloudFront, AWS Backup) trước khi vào các bài Lab tiếp theo.
