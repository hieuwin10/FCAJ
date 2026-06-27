---
title: "Worklog Tuần 11"
date: 2026-06-22
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Hoàn thiện thiết kế kiến trúc hệ thống (Architecture Diagram) trên AWS.
* Triển khai thành công hạ tầng mạng (VPC, Subnet, Security Group) và Database (RDS).
* Đưa mã nguồn (Frontend/Backend) lên chạy thực tế trên môi trường AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2   | - Họp chốt thiết kế kiến trúc (Architecture Diagram) <br> - Chuẩn bị file cấu hình hạ tầng | 22/06/2026 | 22/06/2026 | |
| 3   | - Triển khai hạ tầng mạng (VPC, Public/Private Subnets, Internet Gateway) | 23/06/2026 | 23/06/2026 | |
| 4   | - Khởi tạo Database (Amazon RDS / DynamoDB) <br> - Cấu hình IAM Role và Security Group cho các luồng giao tiếp | 24/06/2026 | 24/06/2026 | |
| 5   | - Triển khai Backend lên EC2 (hoặc ECS/Lambda) <br> - Triển khai Frontend lên Amazon S3 & CloudFront | 25/06/2026 | 25/06/2026 | |
| 6   | - Tích hợp hệ thống, test luồng hoạt động <br> - Fix bug và tối ưu hóa <br> - Cập nhật tài liệu README | 26/06/2026 | 26/06/2026 | |


### Kết quả đạt được tuần 11:

* Đã thiết kế và thống nhất xong toàn bộ kiến trúc AWS cho project.
* Triển khai thành công Frontend hosting trên S3 + CloudFront có HTTPS.
* Backend trên EC2 đã kết nối thành công và query được dữ liệu từ RDS.
* Đã khắc phục thành công các lỗi liên quan đến phân quyền IAM và kết nối mạng trong Private Subnet.

