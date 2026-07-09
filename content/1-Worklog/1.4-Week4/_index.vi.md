---
title: "Worklog Tuần 4"
date: 2026-05-04
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Đào sâu lý thuyết về VPC Peering và AWS Transit Gateway cho kiến trúc nhiều VPC.
* Hiểu cách Route 53 Resolver hỗ trợ Hybrid DNS giữa On-premises và AWS.
* Nắm kiến thức cơ bản về AWS Site-to-Site VPN và CloudFormation.

### Các công việc cần triển khai trong tuần này:

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 1 | Tìm hiểu VPC Peering, gồm cơ chế định tuyến và Cross-Peer DNS Resolution. | 04/05/2026 | 05/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 2 | Tìm hiểu AWS Transit Gateway như một giải pháp thay thế mô hình Full-Mesh VPC Peering. | 06/05/2026 | 07/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 3 | Tìm hiểu Route 53 Resolver Inbound/Outbound Endpoint và Resolver Rules cho Hybrid DNS. | 08/05/2026 | 09/05/2026 | https://cloudjourney.awsstudygroup.com/ |
| 4 | Ôn lại kiến thức cơ bản về AWS Site-to-Site VPN và AWS CloudFormation để chuẩn bị cho các bài Lab về Infrastructure as Code. | 10/05/2026 | 10/05/2026 | https://cloudjourney.awsstudygroup.com/ |

### Kết quả đạt được tuần 4:

* Hiểu cách **VPC Peering** kết nối trực tiếp hai VPC và những giới hạn về định tuyến (không hỗ trợ Transitive Peering).

* Hiểu cách **AWS Transit Gateway** đơn giản hóa hạ tầng mạng cho nhiều VPC bằng mô hình Hub-and-Spoke.

* Nắm được vai trò của **Route 53 Resolver** — Inbound/Outbound Endpoint và Resolver Rules — trong việc kết nối DNS On-premises với AWS.

* Ôn lại kiến thức nền tảng về **AWS Site-to-Site VPN** và **AWS CloudFormation**, chuẩn bị cho các bài Lab thực hành sắp tới.

### Kế hoạch tuần tiếp theo:

* Áp dụng lý thuyết vào thực hành: triển khai VPC Peering, Transit Gateway, Hybrid DNS với Route 53 Resolver và Lab VPN Site-to-Site, đồng thời ôn lại AWS Budgets để quản lý chi phí.
