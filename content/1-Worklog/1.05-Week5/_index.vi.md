---
title: "Worklog Tuần 5"
date: 2026-05-11
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Tìm hiểu mô hình trách nhiệm chia sẻ (Shared Responsibility Model) và các dịch vụ bảo mật trên AWS.
* Quản trị định danh và truy cập nâng cao với IAM, Cognito và AWS Organizations.
* Sử dụng AWS Security Hub để theo dõi tình trạng bảo mật của tài nguyên.
* Tự động hóa quản lý hạ tầng bằng AWS Lambda và EventBridge.
* Thực hành quản lý tài nguyên hiệu quả bằng Tags và Resource Groups.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Lý thuyết Module 05 (Phần 1):** <br>&emsp; + Shared Responsibility Model <br>&emsp; + AWS IAM & Amazon Cognito <br>&emsp; + AWS Organizations & Identity Center <br>&emsp; + AWS KMS & Security Hub | 11/05/2026   | 11/05/2026      | [Module 05-01](https://www.youtube.com/watch?v=tsobAlSg19g) <br> [Module 05-02](https://www.youtube.com/watch?v=N_vlJGAqZxo) <br> [Module 05-03](https://www.youtube.com/watch?v=pZ2fgEFK3Vs) <br> [Module 05-04](https://www.youtube.com/watch?v=5oQY8Rogz9Y) <br> [Module 05-05](https://www.youtube.com/watch?v=NW1xrMkNMjU) <br> [Module 05-06](https://www.youtube.com/watch?v=GMihNQojhZc) <br> [Module 05-07](https://www.youtube.com/watch?v=clj2E0rNBEs) |
| 3   | - **Thực hành Lab 18:** Sử dụng AWS Security Hub <br>&emsp; + Kích hoạt Security Hub <br>&emsp; + Đánh giá tuân thủ theo các tiêu chuẩn bảo mật | 12/05/2026   | 12/05/2026      | [Lab 18-02](https://www.youtube.com/watch?v=YnLo4MgOXyA) <br> [Lab 18-03](https://www.youtube.com/watch?v=uIv0GC1XWMY) <br> [Lab 18-04](https://www.youtube.com/watch?v=jPmjicPl1js) |
| 4   | - **Thực hành Lab 22:** Tự động hóa với Lambda <br>&emsp; + Tạo VPC, Security Group & EC2 <br>&emsp; + Thiết lập Slack Webhook <br>&emsp; + Viết Lambda Function tự động Start/Stop Instance | 13/05/2026   | 13/05/2026      | [Lab 22-2.1](https://www.youtube.com/watch?v=esPRIj_zZSQ) <br> [Lab 22-2.2](https://www.youtube.com/watch?v=k-g4wz4Qlfk) <br> [Lab 22-2.3](https://www.youtube.com/watch?v=BivRALFsoxQ) <br> [Lab 22-2.4](https://www.youtube.com/watch?v=j9hGJXIDdBQ) <br> [Lab 22-3](https://www.youtube.com/watch?v=AVhWQOYnj14) <br> [Lab 22-4](https://www.youtube.com/watch?v=7_1A2Jxl7_c) <br> [Lab 22-5.1](https://www.youtube.com/watch?v=-iGkIHh9mXo) <br> [Lab 22-5.2](https://www.youtube.com/watch?v=aq-YDewEyhA) |
| 5   | - **Thực hành Lab 27:** Quản lý Tags & Resource Groups <br>&emsp; + Tạo EC2 với Tags <br>&emsp; + Lọc tài nguyên theo Tag bằng CLI <br>&emsp; + Tạo và quản lý AWS Resource Groups | 14/05/2026   | 14/05/2026      | [Lab 27-2.1.1](https://www.youtube.com/watch?v=ZQsPVBH8m78) <br> [Lab 27-2.1.2](https://www.youtube.com/watch?v=8pZ_PJAFL74) <br> [Lab 27-2.1.3](https://www.youtube.com/watch?v=_0u1kdborw4) <br> [Lab 27-2.2](https://www.youtube.com/watch?v=kYyceAFqsUg) <br> [Lab 27-3](https://www.youtube.com/watch?v=YDAXEiY8TzU) |
| 6   | - **Thực hành Lab 28:** IAM Policy, Role & Switch Role <br>&emsp; + Tạo IAM User, Policy & Role <br>&emsp; + Thực hành Switch Role giữa các Region (Tokyo, Virginia) <br>&emsp; + Kiểm tra giới hạn quyền truy cập | 15/05/2026   | 15/05/2026      | [Lab 28-2.1](https://www.youtube.com/watch?v=vkBJ0Cxc6Nw) <br> [Lab 28-3](https://www.youtube.com/watch?v=XXjEpIRWJBk) <br> [Lab 28-4](https://www.youtube.com/watch?v=pJWANviu8QM) <br> [Lab 28-5.1](https://www.youtube.com/watch?v=ho5mIhGUows) <br> [Lab 28-5.2.1](https://www.youtube.com/watch?v=5rOiXP7rq9w) <br> [Lab 28-5.2.2](https://www.youtube.com/watch?v=7Qu8QwAsU_c) <br> [Lab 28-5.2.3](https://www.youtube.com/watch?v=zBKV-6mZ_vI) <br> [Lab 28-5.2.4](https://www.youtube.com/watch?v=Yr-09VhrNHU) |


### Kết quả đạt được tuần 5:

* Nắm vững kiến thức về quản lý danh tính (Identity Management) và bảo mật dữ liệu.
* Biết cách sử dụng AWS Organizations để quản lý nhiều tài khoản AWS tập trung.
* Triển khai thành công kịch bản tự động hóa đơn giản với AWS Lambda.
* Thành thạo kỹ năng phân loại tài nguyên bằng Tagging để quản lý chi phí và bảo mật.
* Hiểu rõ cơ chế ủy quyền (Delegation) thông qua IAM Roles.
* ...


