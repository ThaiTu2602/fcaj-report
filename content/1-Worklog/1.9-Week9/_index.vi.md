---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Triển khai xây dựng phần giao diện (Frontend) và phần xử lý logic (Backend) cho dự án tốt nghiệp.
* Thiết kế và cấu hình cơ sở dữ liệu NoSQL cho dự án bằng **Amazon DynamoDB**.
* Tích hợp dịch vụ **Amazon Cognito** để quản lý người dùng, xử lý xác thực và đăng nhập bảo mật.

### Các công việc cần triển khai trong tuần này:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 | **Xây dựng giao diện Frontend** <br>- Thiết kế và phát triển các trang giao diện chính của dự án <br>- Xây dựng các component tái sử dụng <br>- Cấu hình routing và navigation | 15/06/2026 | 16/06/2026 | |
| 3 | **Phát triển Backend cho dự án** <br>- Tạo các Lambda Functions xử lý logic nghiệp vụ của dự án <br>- Thiết kế và triển khai REST API với API Gateway <br>- Xây dựng các endpoint CRUD cho từng chức năng | 17/06/2026 | 18/06/2026 | |
| 4 | **Thiết kế cơ sở dữ liệu DynamoDB** <br>- Phân tích yêu cầu dữ liệu và thiết kế Data Model <br>- Tạo các bảng DynamoDB với Partition Key và Sort Key phù hợp <br>- Cấu hình Global Secondary Index (GSI) cho các truy vấn phức tạp | 19/06/2026 | 19/06/2026 | |
| 5 | **Tích hợp Amazon Cognito** <br>- Tạo User Pool để quản lý người dùng <br>- Cấu hình quy trình đăng ký (Sign Up) và đăng nhập (Sign In) <br>- Thiết lập xác thực đa yếu tố (MFA) và chính sách mật khẩu | 20/06/2026 | 20/06/2026 | |
| 6 | **Tích hợp Cognito vào ứng dụng** <br>- Kết nối Frontend với Amazon Cognito cho luồng xác thực <br>- Cấu hình Cognito Identity Pool để cấp quyền truy cập tài nguyên AWS <br>- Kiểm tra luồng đăng ký, đăng nhập và phân quyền end-to-end | 21/06/2026 | 21/06/2026 | |

### Kết quả đạt được tuần 9:

* **Xây dựng giao diện Frontend cho dự án**: Thiết kế và phát triển các trang giao diện chính với các component tái sử dụng, hệ thống routing và navigation hoàn chỉnh.
* **Triển khai Backend với kiến trúc Serverless**: Xây dựng các Lambda Functions xử lý logic nghiệp vụ, thiết kế REST API với API Gateway và các endpoint CRUD cho từng chức năng của dự án.
* **Thiết kế cơ sở dữ liệu NoSQL tối ưu**: Phân tích yêu cầu dữ liệu, tạo các bảng DynamoDB với cấu trúc khóa phù hợp và cấu hình Global Secondary Index (GSI) để hỗ trợ các truy vấn phức tạp.
* **Tích hợp hệ thống xác thực Amazon Cognito**: Thiết lập User Pool quản lý người dùng, cấu hình quy trình đăng ký/đăng nhập bảo mật với MFA và chính sách mật khẩu mạnh.
* **Hoàn thành luồng xác thực end-to-end**: Kết nối Frontend với Cognito, cấu hình Identity Pool để cấp quyền truy cập tài nguyên AWS, kiểm tra thành công toàn bộ luồng đăng ký, đăng nhập và phân quyền.
