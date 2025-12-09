---
title: "Worklog Tuần 8"
date: 2025-10-28
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

>

### Mục tiêu tuần 8: 

* **Hoàn thành kỳ thi giữa kỳ** (Ngày 31/10) với kết quả tốt.
* Bắt đầu triển khai các chức năng **CRUD (Create, Read, Update, Delete)** cơ bản cho dự án **Travel-Guided**.
* Lên kế hoạch chi tiết cho việc tích hợp **dịch vụ Serverless AI của AWS** (như **Rekognition**) vào dự án.
* Tiếp tục **củng cố kiến thức AWS** trọng tâm phục vụ cho dự án (Lambda, DynamoDB, API Gateway).
* Học cách xác thực người dùng trong ứng dụng bằng JWT (JSON Web Tokens).
* Triển khai authorization để hạn chế truy cập vào các phần khác nhau của ứng dụng.

---

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Ôn tập tổng hợp lần cuối** các kiến thức chuẩn bị cho thi giữa kì. <br> - Rà soát lại các câu hỏi khó, các khái niệm dễ nhầm lẫn (IAM, Security Group, NACL). | 28/10/2025 | 28/10/2025 | Ghi chú cá nhân, AWS Builders |
| 2 | - Chuẩn bị tâm lý và công cụ cho kỳ thi. <br> - **Thực hành:** Bắt đầu setup môi trường phát triển cho dự án **Travel-Guided**. | 29/10/2025 | 30/10/2025 | |
| 3 | - **Thi giữa kỳ** (Ngày 31/10) - Hoàn thành mục tiêu quan trọng nhất. | 31/10/2025 | 31/10/2025 | |
| 4 | - Bắt đầu triển khai chức năng **CRUD cơ bản** đầu tiên (Ví dụ: tạo bài viết, cập nhập được bài viết). <br> - Tìm hiểu và triển khai thử nghiệm **AWS Lambda** và **DynamoDB** (để xây dựng API Serverless). | 01/11/2025 | 01/11/2025 | Tài liệu AWS Lambda & DynamoDB |
| 5 | - **Lên kế hoạch tích hợp Serverless AI:** <br> &emsp; + Nghiên cứu **AWS Rekognition** và các chức năng sẽ dùng (phân tích ảnh địa điểm, nhận diện đối tượng...). <br> &emsp; + Xác định luồng dữ liệu (S3 -> Lambda -> Rekognition) và các thành phần cần thiết. | 02/11/2025 | 02/11/2025 | Tài liệu AWS Rekognition, YouTube |
| 7 | Tìm hiểu về JWT cho xác thực người dùng. | 24/01/2026 | 24/01/2026 | [JWT Documentation](https://jwt.io/) |
| 8 | Triển khai xác thực người dùng trong ứng dụng bằng JWT. | 25/01/2026 | 25/01/2026 | - |
| 9 | Học cách quản lý JWT tokens trong React (lưu trữ trong localStorage/sessionStorage). | 26/01/2026 | 26/01/2026 | - |
| 10 | Thiết lập authorization để hạn chế truy cập vào các route cụ thể dựa trên vai trò người dùng. | 27/01/2026 | 27/01/2026 | [React Router Authentication](https://reactrouter.com/en/main/start/overview) |
| 11 | Bảo mật ứng dụng React với role-based access control sử dụng JWT. | 28/01/2026 | 28/01/2026 | - |
| 12 | Tìm hiểu cách xử lý JWT refresh tokens để quản lý phiên làm việc kéo dài. | 29/01/2026 | 29/01/2026 | [JWT Refresh Tokens](https://auth0.com/blog/refresh-tokens-what-are-they-and-when-to-use-them/) |
| 13 | Triển khai refresh tokens để giữ người dùng đăng nhập theo thời gian. | 30/01/2026 | 30/01/2026 | - |

---

### Kết quả đạt được tuần 8: 

* **Hoàn thành kỳ thi giữa kỳ** (Ngày 31/10).
* **Setup thành công** môi trường phát triển cơ bản cho dự án.
* **Bắt đầu xây dựng** chức năng **Create/Read** đầu tiên của dự án **Travel-Journal** sử dụng **AWS Lambda** và **DynamoDB**.
* **Nghiên cứu và lập kế hoạch chi tiết** cho việc tích hợp dịch vụ **AWS Rekognition** vào dự án, hiểu được luồng xử lý ảnh.
* **Củng cố kiến thức** về các dịch vụ Serverless quan trọng (Lambda, DynamoDB) phục vụ cho phát triển dự án.
* Triển khai thành công xác thực người dùng bằng JWT trong ứng dụng React.
* Thiết lập role-based authorization để hạn chế truy cập vào các route và tài nguyên cụ thể.
* Triển khai JWT refresh tokens để quản lý phiên làm việc.