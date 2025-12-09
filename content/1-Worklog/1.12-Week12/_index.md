---
title: "Worklog Week 12"
date: 2025-11-25
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Week 12 Objectives: 

* **Complete 100% of the basic CRUD functionalities** and **AI image processing** (including the Update function).
* **Upgrade the image processing architecture** by integrating **SQS** for asynchronous processing and clear flow segmentation.
* **Finalize essential missing project features:** Security, Map Pinning, and SNS.
* **Complete the main interfaces** of the Frontend, prepare for domain name purchase, and **attend the final AWS Cloud Mastery Series event**.
* Finalize the project with bug fixes and UI/UX improvements.
* Prepare a project presentation to showcase your work, including both AWS and frontend technologies.

---

### Tasks to be Deployed This Week:

| Day | Task | Start Date | Completion Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Finalize Update Function and AI:** Resolve remaining bugs (Sub ID, Rekognition) to ensure CRUD and image processing are fully functional. | 25/11/2025 | 25/11/2025 | Mentor Guidance, Backend Codebase |
| 2 | - **Upgrade AI Flow with SQS:** Implement **AWS SQS** to create an asynchronous image processing queue, enhancing flow segmentation and performance under high load. <br> - **Define Clear Processing Flows:** Redefine the data flow (Upload -> S3 -> SQS -> Lambda (AI) -> DynamoDB). | 26/11/2025 | 26/11/2025 | AWS SQS Documentation, Lambda Architecture |
| 3 | - **Frontend Interface Finalization:** Complete interfaces for the main pages (Homepage, Article Detail, Personal Management Page). <br> - **Implement Map Pinning:** Integrate Map Pinning functionality for posts, utilizing geo data in DynamoDB or an appropriate map service. | 27/11/2025 | 27/11/2025 | Frontend Codebase, DynamoDB Geo |
| 4 | - **Finalize Security (Authorization):** Optimize authentication and permissions (IAM Policy/Cognito), especially accurate `Sub` retrieval for user operations. <br> - **Implement SNS:** Integrate **AWS SNS** for basic notification features (e.g., notification when a post is successfully processed/uploaded). | 28/11/2025 | 28/11/2025 | AWS SNS, Cognito/IAM Documentation |
| 5 | - **Attend the Final AWS Cloud Mastery Series Event:** Receive overall project guidance, review and finalize missing parts (domain, security, SNS) before the demo. <br> - **Domain Name:** Conduct research and prepare for purchasing the website domain, configuring basic DNS (Route 53) as necessary (based on mentor guidance). | 29/11/2025 | 29/11/2025 | Mentor, AWS Cloud Mastery Series, Route 53 |
| 7 | Review the entire project and fix any bugs in the app. | 25/11/2025 | 25/11/2025 | - |
| 8 | Optimize UI/UX design based on feedback and testing. | 26/11/2025 | 26/11/2025 | - |
| 9 | Prepare a project presentation covering both frontend and AWS integration. | 27/11/2025 | 27/11/2025 | - |
| 10 | Create a technical report outlining the architecture, technologies, and process used. | 28/11/2025 | 28/11/2025 | - |
| 11 | Conduct a demo of your final project. | 29/11/2025 | 29/11/2025 | - |
| 12 | Make final adjustments to the app based on demo feedback. | 30/11/2025 | 30/11/2025 | - |
| 13 | Submit the final project and documentation. | 01/12/2025 | 01/12/2025 | - |

---

### Week 12 Achievements: 

* **Completed 100% of basic CRUD functionalities** and **AI image processing**, ensuring system stability.
* **Upgraded the image processing architecture** by integrating **SQS** and defining clear asynchronous processing flows, improving performance and reliability.
* **Finalized essential features:** Implemented Security, Map Pinning, and SNS notifications.
* **The basic Frontend interface is complete**, ready for presentation.
* **Successfully participated in the final AWS Cloud Mastery Series event**, receiving comprehensive guidance for project completion.
* **Research for domain name purchase** has been conducted and planned.
* The project has reached **Demo Readiness** status.
* Completed the project with all frontend and AWS integrations.
* Successfully deployed the app, fixed bugs, optimized UI/UX, and showcased the final project.