---
title: "Worklog Week 11"
date: 2025-11-18
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives: 

* **Participate in AWS Cloud Mastery Series #2** to continue resolving specialized technical issues.
* **Refactor and standardize the Frontend structure** for improved stability and maintainability.
* **Implement a Multi-Stack architecture** to optimize deployment speed and Serverless project management.
* **Integrate basic CRUD functionalities with AI Image Processing** (using Rekognition) into the website.
* **Completely resolve deployment errors** (especially CORS issues) to stabilize the system.
* Learn about API Gateway and Lambda functions in AWS.
* Integrate AWS API Gateway with your React app for dynamic functionality.

---

### Tasks to be Deployed This Week:

| Day | Task | Start Date | Completion Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Participate in AWS Cloud Mastery Series #2 (Nov 17th):** Continue receiving guidance and addressing deeper technical questions about authorization errors and the AI workflow. | 17/11/2025 | 17/11/2025 | Mentor, AWS Cloud Mastery Series |
| 2 | - **Frontend Structure Unification and Refactor:** Hold team meeting to standardize the Frontend code structure for maintainability. <br> - **Research Multi-Stack Solution:** Begin analyzing how to split the `template.yaml` file into smaller Stacks (Multi-Stack) to optimize the `sam deploy` process. | 18/11/2025 | 18/11/2025 | Serverless Architecture Docs |
| 3 | - **Implement Multi-Stack Architecture:** Start splitting and configuring separate Stacks (e.g., API Backend Stack, Frontend Hosting Stack). <br> - **Proceed with AI Image Processing Integration:** Combine basic CRUD functions with image processing logic (e.g., calling Rekognition API/S3 trigger) in preparation for the Update function. | 19/11/2025 | 19/11/2025 | Backend Codebase, AWS Rekognition |
| 4 | - **Error Encountered after AI Integration:** The system faced errors after combining AI functionality, necessitating a full Stack deletion and redeployment. <br> - **Leader Develops Backup Stack:** The team leader created a separate, optimized Multi-Stack as a contingency and reference for future optimal deployments. | 20/11/2025 | 20/11/2025 | Leader's Backup Stack |
| 5 | - **Persistent CORS Error:** After redeploying, the CORS issue re-emerged. <br> - **In-depth CORS Debugging:** Spent time thoroughly analyzing the root cause and permanently fixing the CORS error, ensuring correct header configuration on both API Gateway and Lambda. | 21/11/2025 | 21/11/2025 | API Gateway/Lambda Configuration |
| 6 | - **Team Meeting and Project Stabilization:** Held a team meeting to review the new Frontend structure, stabilize the main project Stack, and synchronize the fixes for CORS and basic template errors. <br> - **Optimization for Maintenance:** Finalized the solution to use a separate stack (developed by the leader) for flexibility and easier optimization in future development. | 22/11/2025 | 22/11/2025 | New Structure Report |
| 7 | Study AWS API Gateway for creating RESTful APIs. | 17/11/2025 | 17/11/2025 | [API Gateway Docs](https://docs.aws.amazon.com/apigateway/) |
| 8 | Learn about AWS Lambda functions for backend logic. | 18/11/2025 | 18/11/2025 | [AWS Lambda Docs](https://docs.aws.amazon.com/lambda/) |
| 9 | Integrate API Gateway with AWS Lambda for dynamic functionality. | 19/11/2025 | 19/11/2025 | - |
| 10 | Connect the API Gateway with your React frontend for dynamic interactions. | 20/11/2025 | 20/11/2025 | - |
| 11 | Learn about CORS in API Gateway and handle it with your React app. | 21/11/2025 | 21/11/2025 | [API Gateway CORS](https://docs.aws.amazon.com/apigateway/latest/developerguide/how-to-cors.html) |
| 12 | Deploy and test your Lambda functions and API Gateway endpoints. | 22/11/2025 | 22/11/2025 | - |
| 13 | Integrate and optimize API calls between the frontend and backend. | 23/11/2025 | 23/11/2025 | - |

---

### Week 11 Achievements: 

* **Participated in AWS Cloud Mastery Series #2**, gaining deeper knowledge of Serverless, Rekognition, and solutions for authorization errors.
* **Successfully refactored the Frontend** and standardized the overall project structure, improving maintainability.
* **Implemented the Multi-Stack architecture** (or at least established a reliable solution/backup stack), which speeds up deployment and simplifies resource management.
* **Completely resolved the persistent CORS error** after identifying the root cause, ensuring stable communication between Frontend and Backend.
* **Acquired knowledge on fixing basic Template errors** and gained a clearer understanding of AWS SAM deployment issues.
* **Developed a separate stack for backup/optimization**, enhancing project flexibility and safety during future major updates.
* The project has moved into the AI functionality testing phase, and although errors were encountered, a clear path for troubleshooting has been established.
* Successfully integrated API Gateway with AWS Lambda to create dynamic backend functionality for your app.
* Configured CORS and connected the frontend to the backend API for dynamic data handling.