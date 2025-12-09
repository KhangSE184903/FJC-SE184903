---
title: "Worklog Tuần 9"
date: 2025-11-04
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

>

### Mục tiêu tuần 9: 

* Hoàn tất quá trình chuyển đổi sang mô hình phát triển **AWS SAM (Serverless Application Model)**.
* **Tái cấu trúc (Refactor)** và triển khai lại các chức năng CRUD cơ bản theo cấu trúc SAM.
* Giải quyết các vấn đề liên quan đến môi trường để đạt được trạng thái **Deploy thành công** lên AWS.
* Tích hợp **Docker** để chuẩn hóa môi trường `sam build`.
* Hiểu về Progressive Web Apps (PWA) và giúp ứng dụng React có thể hoạt động offline.
* Sử dụng Service Worker cho caching và cải thiện hiệu năng/PWA.

---

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Nghiên cứu chuyên sâu về AWS SAM:** Tìm hiểu cấu trúc `template.yaml`, cách thức hoạt động của các tài nguyên Serverless (Lambda, API Gateway) trong mô hình SAM. <br> - Lập kế hoạch chi tiết cho việc chuyển đổi mã nguồn đã có sang cấu trúc SAM. | 04/11/2025 | 04/11/2025 | Tài liệu AWS SAM, AWS Study Group |
| 2 | - **Tái cấu trúc mã nguồn:** Bắt đầu viết lại các chức năng CRUD cơ bản (tạo/cập nhật bài viết) theo khuôn mẫu của SAM (Handlers và Event Triggers). <br> - **Tích hợp Docker:** Cài đặt và cấu hình Docker để đảm bảo phiên bản Python phù hợp cho quá trình `sam build`. | 05/11/2025 | 06/11/2025 | Tài liệu Docker, SAM CLI |
| 3 | - **Gỡ lỗi và kiểm thử Local:** Thực hiện `sam local invoke` và `sam local start-api`. <br> - **Gặp sự cố nghiêm trọng** trong môi trường Local (Lỗi dependency, xung đột môi trường, vấn đề kết nối DynamoDB local). | 06/11/2025 | 07/11/2025 | Báo cáo lỗi SAM CLI, Stack Overflow |
| 4 | - **Ra quyết định chiến lược:** Team Backend quyết định chuyển sang chiến lược **deploy-then-test** (triển khai rồi kiểm thử) lên môi trường AWS thật để vượt qua các rào cản gỡ lỗi Local, chấp nhận rủi ro cao. <br> - Tập trung khắc phục các lỗi cấu hình trong `template.yaml` để chuẩn bị cho `sam deploy`. | 07/11/2025 | 08/11/2025 | |
| 5 | - **Triển khai thành công:** Thực hiện `sam deploy --guided` và cuối cùng đã triển khai dự án lên môi trường AWS. <br> - **Xác thực cơ bản:** Kiểm tra các API Endpoint đã được tạo và hoạt động, chứng minh chức năng CRUD đã online. | 08/11/2025 | 08/11/2025 | Log triển khai AWS CloudFormation |
| 7 | Học các kiến thức cơ bản về Progressive Web Apps (PWA) và lợi ích. | 31/01/2026 | 31/01/2026 | [PWA Basics](https://web.dev/progressive-web-apps/) |
| 8 | Tìm hiểu Service Worker trong PWA và cách thiết lập trong ứng dụng React. | 01/02/2026 | 01/02/2026 | [Service Worker Guide](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) |
| 9 | Triển khai Service Worker để kích hoạt chế độ offline cho ứng dụng React. | 02/02/2026 | 02/02/2026 | - |
| 10 | Sử dụng các chiến lược caching với Service Worker để cải thiện hiệu năng. | 03/02/2026 | 03/02/2026 | - |
| 11 | Triển khai Push Notifications trong ứng dụng React bằng Service Worker. | 04/02/2026 | 04/02/2026 | [Push Notifications with PWA](https://web.dev/notifications/) |
| 12 | Kiểm thử ứng dụng như một PWA và xác nhận khả năng offline. | 05/02/2026 | 05/02/2026 | - |
| 13 | Tối ưu ứng dụng cho việc cài đặt PWA (manifest, icons, v.v.). | 06/02/2026 | 06/02/2026 | [PWA Installation Guide](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Installing) |

---

### Kết quả đạt được tuần 9: 

* **Hoàn thành việc chuyển đổi** công nghệ sang mô hình phát triển **AWS SAM** cho toàn bộ dự án.
* **Tái cấu trúc thành công** các chức năng CRUD cơ bản vào cấu trúc Serverless của SAM.
* Đã giải quyết được vấn đề môi trường bằng cách sử dụng **Docker** để đảm bảo quá trình `sam build` diễn ra chính xác với phiên bản Python yêu cầu.
* **Đạt được cột mốc quan trọng:** Deploy thành công dự án lên môi trường AWS, vượt qua các trục trặc gỡ lỗi Local.
* **Dự án Travel-Guided** đã có phiên bản API hoạt động trên môi trường Cloud thực tế (mặc dù vẫn cần kiểm thử sâu hơn).
* Triển khai thành công một PWA với hỗ trợ offline bằng Service Worker.
* Tích hợp Push Notifications và chiến lược caching để cải thiện hiệu năng và trải nghiệm.