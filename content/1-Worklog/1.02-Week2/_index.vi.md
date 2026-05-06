---
title: "Worklog Tuần 2"
date: 2026-04-20
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Thực hành và nắm vững các bài Lab cơ bản trong Module 1.
* Hiểu cách cấu hình bảo mật người dùng (IAM), MFA và quản lý chi phí (Budgets).
* **Nâng cao**: Làm chủ các kỹ thuật kết nối mạng phức tạp (VPC Peering và Transit Gateway).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Thực hành tạo tài khoản và cấu hình bảo mật MFA <br> - Tạo Admin Group và Admin User | 20/04/2026 | 20/04/2026 | [Lab 01-01: Create account](https://www.youtube.com/watch?v=waR5S_lljrk) <br> [Lab 01-02: Setup MFA](https://www.youtube.com/watch?v=1dG5xutGbr4) <br> [Lab 01-03: Admin Setup](https://www.youtube.com/watch?v=b9pK1oG534Q) |
| 3 | - Thực hành quản lý chi phí với AWS Budgets (Cost, Usage, RI, Savings Plans Budgets) <br> - Xóa các Budget sau khi thực hành xong | 21/04/2026 | 21/04/2026 | [Lab 07: Manage usage costs](https://000007.awsstudygroup.com/) |
| 4 | - Lý thuyết Module 2: AWS Virtual Private Cloud (VPC) <br> - VPC Security, Multi VPC, VPN, DirectConnect, LoadBalancer | 22/04/2026 | 22/04/2026 | [Playlist FCJ 2025](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_uND8hLn1i) |
| 5 | - Thực hành Lab 03: Amazon VPC <br> - Thực hành Lab 10: Amazon Route 53 | 23/04/2026 | 23/04/2026 | [Lab 03: VPC](https://000003.awsstudygroup.com/) <br> [Lab 10: Route53](https://000010.awsstudygroup.com/) |
| 6 | - Thực hành Lab 11: AWS CLI | 24/04/2026 | 24/04/2026 | [Lab 11: AWS CLI](https://000011.awsstudygroup.com/) |
| 7 | - Thực hành Lab 09: AWS Support Packages <br> - **Thực hành Lab 19: VPC Peering (CLI)** <br> - **Thực hành Lab 20: AWS Transit Gateway (CLI)** | 25/04/2026 | 25/04/2026 | [Lab 09: AWS Support](https://000009.awsstudygroup.com/) <br> [Lab 19: VPC Peering](https://000019.awsstudygroup.com/) <br> [Lab 20: Transit Gateway](https://000020.awsstudygroup.com/) |


### Kết quả đạt được tuần 2:

* Hoàn thành các bài thực hành Lab của Module 1 và Module 2 (Lab 01 - Lab 20).
* Nắm vững cách bảo vệ tài khoản bằng MFA và phân quyền Admin Group/User qua IAM.
* Sử dụng thành thạo AWS CLI để triển khai hạ tầng một cách tự động và chuyên nghiệp.
* **Đặc biệt (Thực hiện trong ngày 25/04)**: 
    - **Lab 19 (VPC Peering)**: Kết nối thành công các VPC riêng biệt, cấu hình Route Table và Security Group để thông mạng nội bộ.
    - **Lab 20 (Transit Gateway)**: Xây dựng hệ thống mạng tập trung (Hub-and-Spoke), kết nối 4 VPC thông qua một Gateway trung tâm duy nhất, giúp tối ưu hóa quản trị mạng quy mô lớn.
* Hiểu rõ cách ghi nhật ký thực thi (Terminal Logs) để theo dõi và debug hệ thống hiệu quả.

### Nhật ký thực hành đặc biệt (Lab 19 & 20):
Toàn bộ quá trình thực hiện 2 bài Lab này đã được tài liệu hóa chi tiết trong thư mục:
- `lab/19/`: VPC Peering (Full Logs & Scripts)
- `lab/20/`: AWS Transit Gateway (Full Logs & Scripts)
- Phương pháp triển khai: Sử dụng **AWS CLI kết hợp PowerShell scripts** để tối ưu hóa thời gian và đảm bảo tính chính xác.
