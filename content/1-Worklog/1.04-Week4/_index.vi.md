---
title: "Worklog Tuần 4"
date: 2026-05-04
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Tìm hiểu các dịch vụ lưu trữ nâng cao (Advanced Storage) trên AWS.
* Hiểu và thực hành cơ chế sao lưu dữ liệu với AWS Backup.
* Nắm vững các tính năng nâng cao của S3 và cách di chuyển dữ liệu (VM Import/Export).
* Làm quen với Storage Gateway và giải pháp lưu trữ Hybrid Cloud.
* Sử dụng Amazon FSx cho các hệ thống tệp tin chuyên dụng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - **Lý thuyết Module 04:** <br>&emsp; + Các dịch vụ lưu trữ trên AWS <br>&emsp; + Amazon S3 (Access Point, Storage Class) <br>&emsp; + S3 Static Website, CORS, Glacier <br>&emsp; + Snow Family, Storage Gateway, AWS Backup | 04/05/2026   | 04/05/2026      | [Module 04-01](https://www.youtube.com/watch?v=hsCfP0IxoaM) <br> [Module 04-02](https://www.youtube.com/watch?v=_yunukwcAwc) <br> [Module 04-03](https://www.youtube.com/watch?v=mPBjB6Ltl_Q) <br> [Module 04-04](https://www.youtube.com/watch?v=YXn8Q_Hpsu4) |
| 3   | - **Thực hành Lab 13:** Triển khai AWS Backup cho hệ thống <br>&emsp; + Tạo S3 Bucket & hạ tầng <br>&emsp; + Tạo Backup Plan <br>&emsp; + Thiết lập thông báo (Notifications) <br>&emsp; + Kiểm tra khôi phục (Restore) | 05/05/2026   | 05/05/2026      | [Lab 13-02.1](https://www.youtube.com/watch?v=IHxgFMlL3y8) <br> [Lab 13-02.2](https://www.youtube.com/watch?v=ZQtDG-DBiYw) <br> [Lab 13-03](https://www.youtube.com/watch?v=cmIMSqeqPr4) <br> [Lab 13-04](https://www.youtube.com/watch?v=I9ISH11xIS8) <br> [Lab 13-05](https://www.youtube.com/watch?v=fZeMSyE0Spc) <br> [Lab 13-06](https://www.youtube.com/watch?v=lRbXC9UXqdo) |
| 4   | - **Thực hành Lab 14:** S3 Advanced & VM Import/Export <br>&emsp; + Xuất/Tải máy ảo lên AWS <br>&emsp; + Import máy ảo thành AMI <br>&emsp; + Cấu hình S3 ACL & Export ngược lại | 06/05/2026   | 06/05/2026      | [Lab 14-01](https://www.youtube.com/watch?v=Yr6oD4btfZg) <br> [Lab 14-02.1](https://www.youtube.com/watch?v=X5PI5rJHIGM) <br> [Lab 14-02.2](https://www.youtube.com/watch?v=ZIQ2uvgLUVQ) <br> [Lab 14-02.3](https://www.youtube.com/watch?v=bsbQQZ3wDzY) <br> [Lab 14-02.4](https://www.youtube.com/watch?v=Yi60WeqqNWw) <br> [Lab 14-03.1](https://www.youtube.com/watch?v=8klJUbKLLu8) <br> [Lab 14-03.2](https://www.youtube.com/watch?v=qDCTqoSZ5Dw) <br> [Lab 14-05](https://www.youtube.com/watch?v=Ipql97gmQjk) |
| 5   | - **Thực hành Lab 24:** Cấu hình Storage Gateway <br>&emsp; + Tạo Storage Gateway & File Shares <br>&emsp; + Mount File Shares lên máy On-premises | 07/05/2026   | 07/05/2026      | [Lab 24-2.1](https://www.youtube.com/watch?v=B3R87qxarWk) <br> [Lab 24-2.2](https://www.youtube.com/watch?v=PaEv0YFVVhI) <br> [Lab 24-2.3](https://www.youtube.com/watch?v=mW1Gxu8AT8c) <br> [Lab 24-3](https://www.youtube.com/watch?v=JqcvArbGqkI) |
| 6   | - **Thực hành Lab 25:** Amazon FSx cho Windows File Server <br>&emsp; + Tạo Multi-AZ file system (SSD/HDD) <br>&emsp; + Tạo File Shares & Kiểm tra hiệu năng <br>&emsp; + Deduplication, Shadow copies, Quotas <br>&emsp; + Scale dung lượng & băng thông | 08/05/2026   | 08/05/2026      | [Lab 25-2.2](https://www.youtube.com/watch?v=4tA3kOTx_Eo) <br> [Lab 25-2.3](https://www.youtube.com/watch?v=9FgS3XS-OdM) <br> [Lab 25-3](https://www.youtube.com/watch?v=yWtiaolQYA8) <br> [Lab 25-4](https://www.youtube.com/watch?v=I62tZyFpBB8) <br> [Lab 25-5](https://www.youtube.com/watch?v=PztdGJgnn_g) <br> [Lab 25-6](https://www.youtube.com/watch?v=OtzLyHj0CeM) <br> [Lab 25-7](https://www.youtube.com/watch?v=8b6XqckuaQM) <br> [Lab 25-8](https://www.youtube.com/watch?v=_3mmmmbqL-A) <br> [Lab 25-9](https://www.youtube.com/watch?v=E3Qo1NDhgqo) <br> [Lab 25-11](https://www.youtube.com/watch?v=xrFg8Yz_eMA) <br> [Lab 25-12](https://www.youtube.com/watch?v=kphXUpKfMS4) <br> [Lab 25-13](https://www.youtube.com/watch?v=GPi_Bd-GdFI) |


### Kết quả đạt được tuần 4:

* Hiểu rõ sự khác biệt giữa các dịch vụ lưu trữ: S3, EBS, EFS, FSx và Storage Gateway.
* Thành thạo việc cấu hình và quản lý sao lưu tự động bằng AWS Backup.
* Biết cách tối ưu hóa chi phí S3 thông qua Lifecycle Policies và Storage Classes.
* Triển khai thành công hệ thống tệp tin Hybrid sử dụng Storage Gateway.
* Cấu hình và quản trị thành thạo Amazon FSx cho các ứng dụng doanh nghiệp.

