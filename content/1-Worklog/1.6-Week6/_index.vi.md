---
title: "Worklog Tuần 6"
date: 2025-10-14
weight: 6
chapter: false
pre: "<b>1.6. </b>"
---

> **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả lưu ý này.

## Mục tiêu tuần 6

- Nắm bắt các khái niệm cơ bản về dịch vụ lưu trữ (Storage) của AWS.
- Tiếp tục học Python cơ bản.
- Tái cấu trúc và hoàn thiện sườn code (code skeleton) và sơ đồ kiến trúc cho dự án.
- Tham gia webinar "Reinventing DevSecOps with AWS Generative AI" để khám phá vai trò DevSecOps, các công cụ liên quan và Amazon Q Developer.
- Học xử lý form và validation trong React (Formik hoặc React Hook Form).
- Hiểu cách dùng localStorage và sessionStorage để lưu dữ liệu phía client.

## Các công việc cần triển khai trong tuần này

| STT | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
|-----|----------|--------------|-----------------|----------------|
| 1 | - Tìm hiểu về Amazon S3: khái niệm Bucket, độ bền, và cách host Static Website.<br>- Tìm hiểu S3 Storage Class (S3 Standard, S3 Standard-IA) và Glacier (lưu trữ lạnh). | 14/10/2025 | 15/10/2025 | [Tham khảo tại đây](https://aws.amazon.com/s3/) |
| 2 | - Tìm hiểu AWS Storage Gateway (File, Volume, Tape Gateway).<br>- Nắm khái niệm Object Life Cycle Management.<br>- Tiếp tục học Python cơ bản.<br>- Tham gia webinar "Reinventing DevSecOps with AWS Generative AI" (có sự góp mặt của anh Hoàng Kha). | 16/10/2025 | 17/10/2025 | [Tham khảo tại đây](https://aws.amazon.com/storagegateway/) <br> [Webinar DevSecOps](https://aws.amazon.com/events/) |
| 3 | - Tìm hiểu Disaster Recovery: khái niệm RTO, RPO, chiến lược Backup & Restore.<br>- Tìm hiểu AWS Backup.<br>- Thực hành tạo S3 Bucket, upload file, và cấu hình Static Website.<br>- Khám phá vai trò DevSecOps và các công cụ phổ biến (CI/CD, SAST, DAST, IaC như Terraform). | 18/10/2025 | 19/10/2025 | [Tham khảo tại đây](https://aws.amazon.com/backup/) |
| 4 | - Chỉnh sửa và cập nhật sơ đồ kiến trúc hạ tầng dự án.<br>- Tái cấu trúc sườn code (code skeleton) dựa trên kiến trúc mới.<br>- Thống nhất ngôn ngữ lập trình và framework cho dự án.<br>- Khám phá Gen AI là Amazon Q Developer (trợ lý AI cho phát triển phần mềm). | 20/10/2025 | 21/10/2025 | [Amazon Q Developer](https://aws.amazon.com/q/developer/) |
| 5 | Học xử lý form trong React (controlled vs. uncontrolled components). | 14/10/2025 | 17/10/2025 | [React Forms](https://react.dev/learn) |
| 6 | Tìm hiểu Formik và cách đơn giản hóa form handling & validation. | 18/10/2025 | 20/10/2025 | [Formik Docs](https://formik.org/) |
| 7 | Thiết lập Formik trong ứng dụng React và thực hiện form validation. | 12/01/2026 | 12/01/2026 | - |
| 8 | Xử lý validation phía client (regex, Yup) trong form React. | 13/01/2026 | 13/01/2026 | [Yup Validation](https://github.com/jquense/yup) |
| 9 | Tìm hiểu localStorage và sessionStorage để lưu dữ liệu form và phiên. | 14/01/2026 | 14/01/2026 | [Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API) |
| 10 | Áp dụng localStorage/sessionStorage để lưu dữ liệu người dùng trong app. | 15/01/2026 | 15/01/2026 | - |
| 11 | Xây dựng form lưu dữ liệu vào localStorage và kiểm tra validation. | 16/01/2026 | 16/01/2026 | - |

## Kết quả đạt được tuần 6

- Hiểu và nắm bắt các khái niệm cơ bản về Amazon S3 (Bucket, độ bền, Static Website hosting) và các lớp lưu trữ (S3 Standard, S3 Standard-IA, Glacier).
- Hiểu vai trò của AWS Storage Gateway và các loại Gateway (File, Volume, Tape).
- Nắm được khái niệm Object Life Cycle Management để quản lý dữ liệu hiệu quả.
- Hiểu các khái niệm Disaster Recovery (RTO, RPO) và chiến lược Backup & Restore, cùng với cách sử dụng AWS Backup.
- Hoàn thành thực hành tạo S3 Bucket.
- Tiến bộ trong học Python cơ bản, áp dụng vào các tác vụ đơn giản của dự án.
- Hoàn thiện chỉnh sửa sơ đồ kiến trúc hạ tầng dự án và cập nhật luồng dữ liệu.
- Tái cấu trúc thành công sườn code (code skeleton) với cấu trúc thư mục và file cấu hình phù hợp.
- Thống nhất được ngôn ngữ lập trình và framework chính thức cho dự án.
- Tham gia thành công webinar "Reinventing DevSecOps with AWS Generative AI" (16/10/2025), với sự góp mặt của anh Hoàng Kha, giúp hiểu rõ hơn về việc tái định hình DevSecOps bằng Gen AI.
- Nắm được vai trò DevSecOps: Tích hợp bảo mật vào SDLC, sử dụng công cụ như Jenkins (CI/CD), SonarQube (SAST), OWASP ZAP (DAST), và Terraform (IaC).
- Khám phá Amazon Q Developer: Trợ lý AI generative mạnh mẽ hỗ trợ code generation, testing, vulnerability scanning, và tối ưu hóa phát triển phần mềm trên AWS.
- Thực hiện form handling và validation trong React bằng Formik/Yup.
- Lưu trữ dữ liệu bằng localStorage và sessionStorage trong ứng dụng React.