---
title: "Worklog Tuần 10"
date: 2025-11-11
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


### Mục tiêu tuần 10: 

* **Ổn định môi trường triển khai** AWS SAM/Serverless.
* **Tập trung gỡ lỗi** các vấn đề cốt lõi: CORS, lỗi vòng lặp (loop) trong `template.yaml`.
* **Tích hợp Frontend/Backend** để có thể kiểm thử chức năng hiển thị và thao tác cơ bản trên giao diện người dùng.
* **Hoàn thiện** các chức năng **Read** và **Delete** cơ bản.
* **Tham gia chuỗi sự kiện AWS Cloud Mastery Series** để nhận hướng dẫn và giải đáp thắc mắc về dự án.
* Triển khai ứng dụng React lên AWS S3 và phân phối toàn cầu qua CloudFront.
* Cấu hình S3/CloudFront cho static hosting và tối ưu phân phối.

---

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Gỡ lỗi CORS:** Phân tích cấu hình CORS trong **API Gateway** và các headers phản hồi của **Lambda** để cho phép Frontend truy cập. <br> - **Khắc phục lỗi template loop:** Kiểm tra và tối ưu hóa file `template.yaml` để tránh lỗi vòng lặp khi triển khai (`sam deploy`). | 11/11/2025 | 11/11/2025 | Tài liệu API Gateway/CORS |
| 2 | - Tiếp tục củng cố chức năng **Read** (Hiển thị bài viết): Đảm bảo dữ liệu từ DynamoDB được truy vấn và trả về đúng định dạng JSON cho Frontend. | 12/11/2025 | 12/11/2025 | |
| 3 | - **Tích hợp Frontend:** Bắt đầu kết hợp mã nguồn Frontend vào dự án và kiểm thử các API Endpoint đã deploy. <br> - **Thành công hiển thị** danh sách bài viết trên giao diện. | 13/11/2025 | 13/11/2025 | Giao diện Frontend mẫu |
| 4 | - Triển khai và kiểm thử chức năng **Delete** (Xóa bài viết). <br> - **Gặp lỗi:** Phát hiện vấn đề về **xác thực (Authorization)** và **Sub ID** khi thực hiện chức năng Delete. | 14/11/2025 | 14/11/2025 | |
| 5 | - **Tham gia sự kiện AWS Cloud Mastery Series:** <br>&emsp; + Nhận hướng dẫn và giải đáp các thắc mắc về Serverless, Rekognition. <br> - Phân tích lỗi **Update/Rekognition:** Bắt đầu áp dụng hướng dẫn từ Mentor để giải quyết vấn đề xác thực và lỗi liên quan đến Rekognition. | 15/11/2025 | 15/11/2025 | Mentor, AWS Cloud Mastery Series |
| 7 | Tìm hiểu cách deploy ứng dụng React lên AWS S3. | 07/02/2026 | 07/02/2026 | [AWS S3 Docs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html) |
| 8 | Thiết lập S3 bucket cho static website hosting. | 08/02/2026 | 08/02/2026 | - |
| 9 | Tìm hiểu cấu hình AWS CloudFront để phân phối nội dung toàn cầu. | 09/02/2026 | 09/02/2026 | [CloudFront Docs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html) |
| 10 | Cấu hình S3 bucket và CloudFront cho ứng dụng React. | 10/02/2026 | 10/02/2026 | - |
| 11 | Deploy ứng dụng lên AWS và kiểm thử qua CloudFront. | 11/02/2026 | 11/02/2026 | - |
| 12 | Thiết lập CI/CD với AWS CodePipeline để tự động hóa deploy. | 12/02/2026 | 12/02/2026 | [CodePipeline Docs](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html) |
| 13 | Kiểm thử deploy và tối ưu hiệu năng (nén, caching). | 13/02/2026 | 13/02/2026 | - |

---

### Kết quả đạt được tuần 10: 

* **Khắc phục thành công** lỗi CORS và ổn định quá trình triển khai SAM.
* **Tham gia chuỗi sự kiện AWS Cloud Mastery Series** và thu thập được các thông tin cần thiết để giải quyết các lỗi lớn của dự án.
* **Hoàn thành tích hợp Frontend** và Backend, đạt được giao diện người dùng đầu tiên để kiểm thử.
* **Đã triển khai thành công chức năng Read** (Hiển thị bài viết) và **Delete** (Xóa bài viết) hoạt động trên giao diện web.
* **Xác định và có hướng giải quyết** cho các điểm nghẽn quan trọng:
    * Lỗi xác thực: Lambda không lấy được/xử lý không đúng **Sub ID** từ token Cognito, ảnh hưởng đến các thao tác cần quyền.
    * Lỗi chức năng **Update**: Phụ thuộc vào luồng xử lý ảnh liên quan đến **Rekognition** (đã có hướng dẫn từ Mentor).
* Dự án đã chuyển sang giai đoạn kiểm thử người dùng cơ bản.
* Triển khai thành công ứng dụng React lên AWS S3 và phân phối toàn cầu qua CloudFront.
* Thiết lập CI/CD tự động với AWS CodePipeline cho các lần deploy tiếp theo.
