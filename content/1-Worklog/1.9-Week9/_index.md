---
title: "Worklog Week 9"
date: 2025-11-04
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---



### Week 9 Objectives: 

* Complete the transition to the **AWS SAM (Serverless Application Model)** development model.
* **Refactor** and re-implement the basic CRUD functionalities according to the SAM structure.
* Resolve environment-related issues to achieve a **successful Deployment** status on AWS.
* Integrate **Docker** to standardize the environment for `sam build`.
* Understand Progressive Web Apps (PWA) and make the React app offline-capable.
* Use Service Workers for caching, performance, and PWA features.

---

### Tasks to be Deployed This Week:

| Day | Task | Start Date | Completion Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **In-depth research on AWS SAM:** Understand the `template.yaml` structure and how Serverless resources (Lambda, API Gateway) operate within the SAM model. <br> - Plan the detailed migration of existing source code to the SAM structure. | 04/11/2025 | 04/11/2025 | AWS SAM Documentation, AWS Study Group |
| 2 | - **Source Code Refactoring:** Start rewriting basic CRUD functionalities (create/update posts) using the SAM pattern (Handlers and Event Triggers). <br> - **Docker Integration:** Install and configure Docker to ensure the correct Python version for the `sam build` process. | 05/11/2025 | 06/11/2025 | Docker Documentation, SAM CLI |
| 3 | - **Local Debugging and Testing:** Execute `sam local invoke` and `sam local start-api`. <br> - **Encountered critical issues** in the Local environment (Dependency errors, environment conflicts, DynamoDB local connection issues). | 06/11/2025 | 07/11/2025 | SAM CLI Error Reports, Stack Overflow |
| 4 | - **Strategic Decision:** The Backend Team decided to switch to a **deploy-then-test** strategy on the actual AWS environment to overcome local debugging barriers, accepting the high risk. <br> - Focus on fixing configuration errors in `template.yaml` in preparation for `sam deploy`. | 07/11/2025 | 08/11/2025 | |
| 5 | - **Successful Deployment:** Executed `sam deploy --guided` and finally deployed the project to the AWS environment. <br> - **Basic Verification:** Tested the created and functioning API Endpoints, confirming CRUD functionality is online. | 08/11/2025 | 08/11/2025 | AWS CloudFormation Deployment Logs |
| 6 | Learn the basics of Progressive Web Apps (PWA) and the benefits. | 04/11/2025 | 04/11/2025 | [PWA Basics](https://web.dev/progressive-web-apps/) |
| 7 | Study how Service Workers work in PWAs and set them up in a React app. | 05/11/2025 | 05/11/2025 | [Service Worker Guide](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) |
| 8 | Implement a Service Worker to enable offline functionality in the React app. | 06/11/2025 | 06/11/2025 | - |
| 9 | Use caching strategies with Service Workers to improve performance. | 07/11/2025 | 07/11/2025 | - |
| 10 | Implement Push Notifications in the React app using Service Workers. | 08/11/2025 | 08/11/2025 | [Push Notifications with PWA](https://web.dev/notifications/) |
| 11 | Test the app as a PWA and verify offline capability. | 09/11/2025 | 09/11/2025 | - |
| 12 | Optimize the app for PWA installation (manifest, icons, etc.). | 10/11/2025 | 10/11/2025 | [PWA Installation Guide](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Installing) |

---

### Week 9 Achievements: 

* **Completed the technology transition** to the **AWS SAM** development model for the entire project.
* **Successfully refactored** the basic CRUD functionalities into the SAM Serverless structure.
* Resolved environment issues by using **Docker** to ensure the `sam build` process uses the required Python version correctly.
* **Achieved a critical milestone:** Successfully deployed the project to the AWS environment, overcoming local debugging hurdles.
* The **Travel-Guided project** now has a working API version on a real Cloud environment (though deeper testing is still required).
* Successfully implemented a Progressive Web App (PWA) with offline support using Service Workers.
* Integrated Push Notifications and caching strategies to enhance performance and user engagement.