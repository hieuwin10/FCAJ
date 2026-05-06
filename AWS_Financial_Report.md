# Báo cáo Tài chính AWS (AWS Financial Report)
**Ngày tạo:** 2026-04-29
**Tài khoản:** Mặc định (Default Profile)
**Trạng thái:** Hoàn tất kiểm tra

## 1. Tóm tắt Chi phí (Cost Summary)
Dựa trên dữ liệu từ AWS Cost Explorer, chi phí hiện tại của tài khoản trong tháng 4 năm 2026 là cực kỳ thấp (gần như bằng 0).

| Tháng | Tổng chi phí (USD) |
| :--- | :--- |
| Tháng 02/2026 | 0.00 USD |
| Tháng 03/2026 | 0.00 USD |
| Tháng 04/2026 (Hiện tại) | ~0.00 USD |

## 2. Chi tiết theo Vùng (Region Breakdown)
Người dùng đã yêu cầu kiểm tra 2 vùng: **US (us-east-1)** và **Singapore (ap-southeast-1)**.

### a. Region: Singapore (ap-southeast-1)
- **Tổng chi phí:** ~0.00 USD
- **Các dịch vụ phát sinh chi phí nhỏ (Usage):**
    - EC2 - Other: $0.0000002884 (Thường là do EBS hoặc địa chỉ IP nếu có, nhưng hiện tại không tìm thấy tài nguyên nào đang hoạt động).
- **Tài nguyên phát hiện:** Không tìm thấy (0 Instance, 0 EBS, 0 NAT Gateway, 0 EIP).

### b. Region: US East (us-east-1)
- **Tổng chi phí:** ~0.00 USD
- **Các dịch vụ phát sinh chi phí nhỏ (Usage):**
    - Amazon Simple Storage Service: $0.0000000418.
- **Tài nguyên phát hiện:** 
    - 1 Default VPC (`vpc-0c336a95aa0b0eecd`). (Lưu ý: VPC mặc định không tốn phí).
    - 0 Instance, 0 EBS, 0 NAT Gateway, 0 EIP, 0 S3 Buckets.

## 3. Danh sách Tài nguyên Kiểm tra (Resource Inventory)
Chúng tôi đã thực hiện quét kỹ lưỡng các tài nguyên có khả năng gây tốn phí:

| Tài nguyên | Singapore (ap-southeast-1) | US East (us-east-1) |
| :--- | :--- | :--- |
| EC2 Instances | 0 | 0 |
| EBS Volumes | 0 | 0 |
| NAT Gateways | 0 | 0 |
| Elastic IPs | 0 | 0 |
| Load Balancers | 0 | 0 |
| RDS Databases | 0 | 0 |
| S3 Buckets | 0 | 0 |
| Lambda Functions | 0 | 0 |
| CloudFront Dist. | 0 (Global) | 0 (Global) |

## 4. Kết luận & Khuyến nghị
- **Kết luận:** Hiện tại không có tài nguyên nào đang hoạt động (Running) có khả năng gây ra sự gia tăng đột biến về hóa đơn trong hai vùng đã kiểm tra.
- **Lý do có thể khiến bạn thấy hóa đơn tăng:**
    1. **Sử dụng vượt hạn mức Free Tier:** Có thể bạn đã sử dụng một số dịch vụ vượt quá số giờ miễn phí (ví dụ: >750 giờ EC2 micro).
    2. **Dữ liệu lưu trữ:** Một lượng nhỏ chi phí từ S3 hoặc snapshots cũ (đã được kiểm tra nhưng không thấy snapshots do người dùng sở hữu).
    3. **Vùng khác:** Bạn có thể có tài nguyên ở các vùng khác chưa được quét (tuy nhiên tôi đã quét nhanh toàn bộ vùng cho EC2 và không thấy gì).
    4. **Thuế (Tax):** Đôi khi có một khoản thuế nhỏ được tính vào cuối tháng.

**Hành động đã thực hiện:** 
- Đã quét toàn bộ tài nguyên quan trọng.
- Không tìm thấy tài nguyên nào cần "dọn dẹp" vì tất cả đã trống.

*Lưu ý: Nếu bạn thấy con số trên Console khác với báo cáo này, có thể do dữ liệu Cost Explorer có độ trễ từ 24h.*
