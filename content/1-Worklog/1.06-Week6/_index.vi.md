---
title: "Worklog Tuần 6"
date: 2026-05-18
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---


### Mục tiêu tuần 6:

* Hiểu và quản lý hạn ngạch (Quotas) của các tài nguyên IAM.
* Sử dụng AWS KMS để mã hóa dữ liệu trên S3 và quản lý khóa tập trung.
* Giám sát và truy vết mọi hoạt động trên tài khoản AWS thông qua AWS CloudTrail.
* Sử dụng Amazon Athena để truy vấn log và phân tích sự kiện bảo mật.
* So sánh và thực hành phân biệt giữa Access Keys và IAM Roles để áp dụng Best Practices.
* Sử dụng AWS Secrets Manager để quản lý thông tin nhạy cảm cho ứng dụng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Thực hành Lab 30:** Quản lý IAM User Quota <br>&emsp; + Kiểm tra giới hạn IAM User hiện tại <br>&emsp; + Sử dụng Python Script tạo hàng loạt User <br>&emsp; + Yêu cầu tăng Quota khi cần thiết | 18/05/2026   | 18/05/2026      | [Lab 30-2](https://www.youtube.com/watch?v=J9fI9W9J-t8) <br> [Lab 30-3.1](https://www.youtube.com/watch?v=VzZk_1q-1xM) <br> [Lab 30-3.2](https://www.youtube.com/watch?v=R9o_oO1tSgY) |
| 3   | - **Thực hành Lab 33:** KMS, CloudTrail & Athena <br>&emsp; + Mã hóa S3 Bucket bằng KMS <br>&emsp; + Giám sát truy cập bằng CloudTrail <br>&emsp; + Truy vấn log sự kiện bằng Amazon Athena | 19/05/2026   | 19/05/2026      | [Lab 33-2.1.1](https://www.youtube.com/watch?v=Yf1v2M1XwM0) <br> [Lab 33-2.2](https://www.youtube.com/watch?v=kYyceAFqsUg) <br> [Lab 33-4.1](https://www.youtube.com/watch?v=YDAXEiY8TzU) <br> [Lab 33-5.1](https://www.youtube.com/watch?v=Yr-09VhrNHU) |
| 4   | - **Thực hành Lab 44:** Chính sách phân quyền nâng cao <br>&emsp; + Phân biệt Inline Policy vs Managed Policy <br>&emsp; + Thực hành ủy quyền truy cập (Delegate access) <br>&emsp; + Logic đánh giá Policy của AWS | 20/05/2026   | 20/05/2026      | [Lab 44-2.2](https://www.youtube.com/watch?v=BivRALFsoxQ) <br> [Lab 44-2.5](https://www.youtube.com/watch?v=7_1A2Jxl7_c) <br> [Lab 44-3.1](https://www.youtube.com/watch?v=-iGkIHh9mXo) <br> [Lab 44-3.2](https://www.youtube.com/watch?v=aq-YDewEyhA) |
| 5   | - **Thực hành Lab 48:** Bảo mật thông tin nhạy cảm <br>&emsp; + So sánh Access Keys vs IAM Role cho EC2 <br>&emsp; + Sử dụng AWS Secrets Manager quản lý mật khẩu <br>&emsp; + Audit quyền truy cập tài nguyên | 21/05/2026   | 21/05/2026      | [Lab 48-2.1](https://www.youtube.com/watch?v=vkBJ0Cxc6Nw) <br> [Lab 48-2.2](https://www.youtube.com/watch?v=XXjEpIRWJBk) <br> [Lab 48-3.1](https://www.youtube.com/watch?v=pJWANviu8QM) <br> [Lab 48-3.4](https://www.youtube.com/watch?v=Yr-09VhrNHU) |
| 6   | - **Tổng kết Module 05:** <br>&emsp; + Rà soát lại toàn bộ kiến thức bảo mật <br>&emsp; + Hoàn thiện các bài Lab còn thiếu <br>&emsp; + Chuẩn bị cho Module 06 (Databases) | 22/05/2026   | 22/05/2026      | |


### Kết quả đạt được tuần 6:

* Hiểu rõ cách bảo vệ dữ liệu "at rest" và "in transit" sử dụng dịch vụ mã hóa.
* Có khả năng phân tích và điều tra các sự kiện bất thường trên AWS bằng log.
* Biết cách áp dụng nguyên tắc "Least Privilege" thông qua việc thiết kế Policy chặt chẽ.
* Thành thạo việc sử dụng Roles thay cho Access Keys để tăng tính bảo mật.
* Biết cách quản lý tập trung và tự động xoay vòng mật khẩu với Secrets Manager.
* ...


