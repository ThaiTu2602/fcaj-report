---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Học và nghiên cứu kiến thức nền tảng về hệ thống mạng Cloud với **Amazon VPC**.
* Khởi tạo, cấu hình và tìm hiểu phương thức hoạt động của máy chủ ảo **Amazon EC2**.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Tìm hiểu kiến trúc Amazon VPC** <br>- Nghiên cứu các khái niệm cốt lõi: VPC, Subnet, CIDR Block <br>- Phân biệt Public Subnet và Private Subnet <br>- Tìm hiểu Internet Gateway và Route Table | 04/05/2026 | 04/05/2026 | |
| 3 | **Thực hành tạo VPC** <br>- Tạo VPC với cấu hình CIDR phù hợp <br>- Tạo Public Subnet và Private Subnet <br>- Tạo và gắn Internet Gateway vào VPC <br>- Cấu hình Route Table cho các Subnet | 05/05/2026 | 05/05/2026 | |
| 4 | **Tìm hiểu Amazon EC2** <br>- Nghiên cứu các loại Instance Types (t2, t3, m5, ...) <br>- Tìm hiểu Amazon Machine Image (AMI) <br>- Hiểu về Elastic Block Store (EBS) và các loại volume | 06/05/2026 | 06/05/2026 | |
| 5 | **Thực hành khởi tạo EC2** <br>- Tạo Security Group cho EC2 Instance <br>- Khởi chạy EC2 Instance trong Public Subnet <br>- Cấu hình Key Pair và kết nối SSH vào Instance | 07/05/2026 | 07/05/2026 | |
| 6 | **Cấu hình mạng nâng cao cho EC2** <br>- Khởi chạy EC2 Instance trong Private Subnet <br>- Cấp phát Elastic IP <br>- Tạo NAT Gateway để cho phép Private Instance truy cập Internet <br>- Xác thực kết nối giữa Public và Private EC2 | 08/05/2026 | 09/05/2026 | |

### Kết quả đạt được tuần 3:

* **Nắm vững kiến trúc mạng Amazon VPC**: Hiểu rõ các thành phần cốt lõi của VPC bao gồm Subnet, CIDR Block, Internet Gateway và Route Table, cùng vai trò của chúng trong việc xây dựng hạ tầng mạng Cloud an toàn.
* **Thiết kế mạng VPC phân tầng**: Xây dựng thành công kiến trúc VPC với Public Subnet và Private Subnet, phân tách các tài nguyên theo mức độ truy cập để tăng cường bảo mật.
* **Triển khai máy chủ ảo Amazon EC2**: Khởi tạo và cấu hình các EC2 Instance với Instance Types, AMI và EBS volume phù hợp, nắm bắt quy trình vận hành máy chủ ảo trên Cloud.
* **Cấu hình kết nối an toàn**: Thiết lập Security Group, Key Pair và kết nối SSH để quản trị EC2 Instance từ xa một cách bảo mật.
* **Triển khai NAT Gateway**: Cấu hình NAT Gateway và Elastic IP để cho phép các EC2 Instance trong Private Subnet truy cập Internet chiều đi (outbound) mà không bị lộ trước lưu lượng Internet chiều vào.
* **Xác thực kết nối đầu-cuối**: Kiểm tra thành công giao tiếp giữa các EC2 Instance trong Public và Private Subnet, đảm bảo luồng lưu lượng mạng hoạt động đúng theo thiết kế.
