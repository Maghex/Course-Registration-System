# SAD Project

## System Name
Course-Registration-System

## Course
Systems Analysis and Design (SAD)

## Business Need

The university suffers from human errors during semester course registration periods due to its reliance on manual review of prerequisites and calculation of minimum and maximum credit hours. This project aims to build an automated system that ensures the accurate application of academic regulations, eliminates scheduling conflicts, and reduces the administrative burden on academic advisors.

تعاني الجامعة من اختناقات وأخطاء بشرية متكررة خلال فترات تسجيل المقررات الفصلية نتيجة الاعتماد على المراجعة اليدوية للمتطلبات السابقة (Pre-requisites) وحساب الحدود القصوى والدنيا للساعات المعتمدة (Credit Hours).يهدف هذا المشروع إلى بناء نظام آلي يضمن تطبيق اللوائح الأكاديمية بدقة، ويزيل التضارب في الجداول، ويخفض العبء الإداري على المرشدين الأكاديميين.


## Project Requirements

- Automated Prerequisite Verification: Automatically prevents students from registering for any course without completing the prerequisite.
- Credit Limits Management: Determines the maximum and minimum credit hours allowed based on GPA and student status (probation, honours, graduation).
- Schedule Check: Immediately detects any scheduling conflicts between lectures or final exams before schedule confirmation.
- Schedule Check: Immediately detects any scheduling conflicts between lectures or final exams before schedule confirmation.


## Feasibility Study
#### Technical feasibility involves assessing the technical risks and the team's ability to implement and maintain the system under pressure:-

- Technology Familiarity: Highly familiar; the system relies on standard web technologies (such as React/Vue for the front end, Node.js/Python for back-end services, and PostgreSQL or MySQL databases).
- Project Size: Medium size. It consists of key modules: Student Management, Course Management, Rules Engine, and Reports Panel.
- System Load Risk: Relatively high during peak registration week (peak load). This requires the adoption of a scalable architecture (cloud scaling/microservices) to handle thousands of concurrent requests without system crashes.
- Compliance with academic regulations: The system is fully aligned with university policies, and even promotes their precise application without bias or unjustified exceptions.
- User Acceptance: Excellent from students and mentors, as it provides a simple and clear interface that replaces complex paperwork.
- Change management and authorisation: Requires basic training for academic advisors on how to handle exception requests and modify study plans.


## Project Documentation

### 1. System Request
[View System Request](docs/01-System-Request/system-request.md)

### 2. Feasibility Study
[View Feasibility Study](docs/02-Feasibility-Study/feasibility-study.md)

### 3. Requirements
[View Requirements](docs/03-Requirements/)

### 4. System Analysis
[View Analysis](docs/04-Analysis/)

### 5. Data Modeling
[View Data Modeling](docs/05-Data-Modeling/)

### 6. System Design
[View System Design](docs/06-System-Design/)

## Diagrams

All diagram source files are available in:

`diagrams/source/`

## Team Members

- Mahmoud ...
- ...
- ...

## Course Information

**Course:** Systems Analysis and Design  
**University:** ...  
**Academic Year:** 2026/2027
