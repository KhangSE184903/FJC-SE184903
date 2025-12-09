---
title: "Worklog Week 10"
date: 2025-11-11
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---



### Week 10 Objectives: 

* **Stabilize the AWS SAM/Serverless deployment environment.**
* **Focus on debugging** core issues: CORS, and loop errors in `template.yaml`.
* **Integrate Frontend/Backend** to enable basic display and interaction testing on the user interface.
* **Complete** the basic **Read** and **Delete** functionalities.
* **Participate in the AWS Cloud Mastery Series event** to receive guidance and address project inquiries.
* Deploy the React app to AWS S3 and serve it globally via CloudFront.
* Configure S3/CloudFront for static website hosting and optimize delivery.

---

### Tasks to be Deployed This Week:

| Day | Task | Start Date | Completion Date | Resources |
| :--- | :--- | :--- | :--- | :--- |
| 1 | - **Debug CORS:** Analyze CORS configuration in **API Gateway** and the response headers of **Lambda** to allow Frontend access. <br> - **Fix template loop error:** Check and optimize the `template.yaml` file to prevent loop errors during deployment (`sam deploy`). | 11/11/2025 | 11/11/2025 | API Gateway/CORS Documentation |
| 2 | - Continue strengthening the **Read** function (Displaying posts): Ensure data is queried from DynamoDB and returned in the correct JSON format for the Frontend. | 12/11/2025 | 12/11/2025 | |
| 3 | - **Frontend Integration:** Start combining the Frontend code with the project and test the deployed API Endpoints. <br> - **Successfully display** the list of posts on the interface. | 13/11/2025 | 13/11/2025 | Sample Frontend interface |
| 4 | - Deploy and test the **Delete** function (Deleting posts). <br> - **Encountered Error:** Identified an issue with **Authorization** and the **Sub ID** when executing the Delete function. | 14/11/2025 | 14/11/2025 | |
| 5 | - **Participation in AWS Cloud Mastery Series:** <br>&emsp; + Received guidance and clarified questions regarding Serverless, Rekognition. <br> - **Analyze Update/Rekognition error:** Begin applying mentor guidance to resolve authorization issues and Rekognition-related errors. | 15/11/2025 | 15/11/2025 | Mentor, AWS Cloud Mastery Series |
| 6 | Study how to deploy a React app to AWS S3. | 07/02/2026 | 07/02/2026 | [AWS S3 Docs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html) |
| 7 | Set up an S3 bucket for static website hosting. | 08/02/2026 | 08/02/2026 | - |
| 8 | Learn how to configure AWS CloudFront to distribute content globally. | 09/02/2026 | 09/02/2026 | [CloudFront Docs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html) |
| 9 | Configure S3 bucket and CloudFront for the React app. | 10/02/2026 | 10/02/2026 | - |
| 10 | Deploy the app to AWS and test via CloudFront. | 11/02/2026 | 11/02/2026 | - |
| 11 | Set up CI/CD pipeline with AWS CodePipeline for automated deployments. | 12/02/2026 | 12/02/2026 | [CodePipeline Docs](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html) |
| 12 | Test deployment and optimize for performance (compression, caching). | 13/02/2026 | 13/02/2026 | - |

---

### Week 10 Achievements: 

* **Successfully fixed** the CORS error and stabilized the SAM deployment process (mitigated template loop errors).
* **Participated in the AWS Cloud Mastery Series event** and gathered necessary information to solve major project bugs.
* **Completed Frontend and Backend integration**, achieving the first user interface for testing.
* **Successfully deployed the Read** (Displaying posts) and **Delete** (Deleting posts) functionalities, which are operational on the web interface.
* **Identified and gained direction** to solve critical bottlenecks:
    * Authorization error: Lambda fails to retrieve/incorrectly process the **Sub ID** from the Cognito token, affecting privileged operations.
    * **Update** function error: Dependent on the image processing workflow involving **Rekognition** (mentor guidance obtained).
* The project has transitioned to the basic user testing phase.
* Successfully deployed the React app to AWS S3 and served it globally using CloudFront.
* Configured a CI/CD pipeline for automated deployments using AWS CodePipeline.

---