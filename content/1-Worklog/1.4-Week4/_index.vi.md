---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Tìm hiểu cách thiết lập hạ tầng Active Directory trong môi trường AWS, cấu hình kết nối thông qua Remote Desktop Gateway (RDGW) để quản trị từ xa an toàn.
* Nghiên cứu các khái niệm về phân giải tên miền lai và chuẩn bị môi trường phục vụ cho việc tích hợp hệ thống DNS.
* Nghiên cứu cơ chế tường lửa bảo mật nâng cao trong VPC: **Security Group** và **Network ACLs**.
* Thực hành triển khai hàng loạt các **Amazon EC2 Instances**.
* Nghiên cứu và cấu hình kết nối bảo mật **Site-to-Site VPN**.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Triển khai hạ tầng Hybrid DNS**<br>- Kết nối tới Remote Desktop Gateway (RDGW)<br>- Triển khai Microsoft Active Directory<br>- Xác thực môi trường Active Directory | 11/05/2026 | 11/05/2026 | ![Lab 10 Hybrid DNS](images/worklog/week3-lab10.png) |
| 3 | **Nghiên cứu Security Group** <br>- Tìm hiểu cơ chế hoạt động của Security Group (Stateful Firewall) <br>- Cấu hình Inbound và Outbound Rules <br>- Thực hành tạo Security Group cho các tầng ứng dụng khác nhau | 12/05/2026 | 12/05/2026 | |
| 4 | **Nghiên cứu Network ACLs** <br>- Tìm hiểu cơ chế hoạt động của Network ACLs (Stateless Firewall) <br>- So sánh sự khác biệt giữa Security Group và Network ACLs <br>- Cấu hình Network ACLs cho các Subnet | 13/05/2026 | 13/05/2026 | |
| 5 | **Triển khai hàng loạt EC2 Instances** <br>- Thực hành khởi chạy nhiều EC2 Instances đồng thời <br>- Cấu hình các Security Group phù hợp cho từng Instance <br>- Kiểm tra kết nối và giao tiếp giữa các Instances | 14/05/2026 | 14/05/2026 | |
| 6 | **Cấu hình Site-to-Site VPN** <br>- Nghiên cứu kiến trúc và hoạt động của AWS Site-to-Site VPN <br>- Tạo Virtual Private Gateway và Customer Gateway <br>- Thiết lập kết nối VPN tunnel <br>- Xác thực kết nối bảo mật giữa môi trường on-premises và AWS | 15/05/2026 | 16/05/2026 | |

### Kết quả đạt được tuần 4:

* **Xây dựng hạ tầng Active Directory và quản trị bảo mật**: Triển khai thành công Microsoft Active Directory trên AWS và thiết lập kết nối an toàn qua Remote Desktop Gateway (RDGW). Quản lý cấu hình định danh và xác thực môi trường Active Directory phục vụ cho mô hình DNS lai.
* **Nắm vững cơ chế Security Group**: Hiểu rõ cách hoạt động của Security Group như một tường lửa Stateful, biết cách cấu hình Inbound/Outbound Rules để kiểm soát lưu lượng truy cập ở cấp Instance.
* **Triển khai Network ACLs**: Cấu hình Network ACLs như một lớp bảo mật bổ sung ở cấp Subnet, nắm rõ sự khác biệt giữa tường lửa Stateful (Security Group) và Stateless (Network ACLs).
* **Triển khai hàng loạt EC2 Instances**: Thực hành khởi chạy và quản lý nhiều EC2 Instances đồng thời, áp dụng các Security Group phù hợp cho từng tầng ứng dụng.
* **Cấu hình kết nối Site-to-Site VPN**: Thiết lập thành công kết nối VPN bảo mật giữa môi trường on-premises và AWS thông qua Virtual Private Gateway và Customer Gateway, đảm bảo dữ liệu được mã hóa khi truyền tải.
* **Tăng cường kiến thức bảo mật hạ tầng**: Tích lũy kinh nghiệm thực tế trong việc triển khai nhiều lớp bảo mật cho hạ tầng mạng AWS, từ tường lửa cấp Instance đến cấp Subnet và kết nối VPN bảo mật.
