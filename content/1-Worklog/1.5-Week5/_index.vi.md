---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Tham gia sự kiện công nghệ do AWS tổ chức.
* Thực hành thiết lập hệ thống phân giải tên miền kết hợp với **Route 53 Resolver (Hybrid DNS)**.
* Cấu hình kết nối trực tiếp giữa các mạng VPC thông qua **VPC Peering**.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Tham gia sự kiện công nghệ AWS** <br>- Tham dự sự kiện công nghệ do AWS tổ chức <br>- Tiếp thu các xu hướng công nghệ Cloud mới nhất <br>- Networking với các chuyên gia và cộng đồng | 18/05/2026 | 18/05/2026 | |
| 3 | **Nghiên cứu Route 53 Resolver** <br>- Tìm hiểu kiến trúc Hybrid DNS với Amazon Route 53 Resolver <br>- Hiểu cách Inbound và Outbound Resolver Endpoints hoạt động <br>- Nghiên cứu các trường hợp sử dụng phân giải DNS lai | 19/05/2026 | 19/05/2026 | |
| 4 | **Thực hành cấu hình Hybrid DNS** <br>- Tạo Route 53 Outbound Endpoint <br>- Tạo các Route 53 Resolver Rules <br>- Tạo Route 53 Inbound Endpoint <br>- Xác thực phân giải DNS hai chiều | 20/05/2026 | 21/05/2026 | |
| 5 | **Nghiên cứu VPC Peering** <br>- Tìm hiểu kiến trúc và các trường hợp sử dụng của VPC Peering <br>- Tạo kết nối VPC Peering Connection giữa hai VPC <br>- Cập nhật Route Tables và Network ACLs | 22/05/2026 | 22/05/2026 | |
| 6 | **Xác thực kết nối liên VPC** <br>- Kích hoạt Cross-Peer DNS Resolution <br>- Kiểm tra kết nối giữa các EC2 Instances chéo VPC <br>- Xác thực phân giải tên miền DNS riêng tư | 23/05/2026 | 23/05/2026 | |

### Kết quả đạt được tuần 5:

* **Tham gia sự kiện công nghệ AWS**: Tham dự sự kiện công nghệ, tiếp thu các xu hướng Cloud mới nhất và mở rộng mạng lưới kết nối với cộng đồng chuyên gia AWS.
* **Xây dựng hạ tầng Hybrid DNS**: Cấu hình Amazon Route 53 Resolver với Inbound và Outbound Endpoints, cho phép phân giải DNS liền mạch giữa tài nguyên AWS và môi trường on-premises.
* **Triển khai phân giải tên miền an toàn cho môi trường Hybrid**: Tạo các Route 53 Resolver Rules để chuyển tiếp truy vấn DNS giữa AWS và mạng on-premises, xác thực phân giải tên miền hai chiều thành công.
* **Thiết lập kết nối riêng tư giữa các VPC**: Cấu hình VPC Peering giữa hai VPC độc lập, cho phép giao tiếp riêng tư trực tiếp mà không cần đi qua Internet công cộng.
* **Kích hoạt Cross-Peer DNS Resolution**: Cấu hình phân giải DNS trên các VPC được kết nối chéo, cho phép các EC2 Instances giao tiếp bằng tên máy chủ DNS riêng tư thay vì địa chỉ IP.
* **Củng cố chuyên môn mạng lai (Hybrid Networking)**: Tích lũy kinh nghiệm thực tế trong thiết kế các giải pháp mạng lai, kết nối riêng tư an toàn giữa các môi trường AWS và hệ thống phân giải tên miền tích hợp.
