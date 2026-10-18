# Course Registration System (CRS)

**جامعة المنوفية**  
**كلية الحاسبات والمعلومات**  
**Menoufia University**  

* **Sad-project**
* **second year**
* **2026-2027**

---

## Team Members

| No. | Name | Section |
|---|---|---|
| 1 | مصطفي محمد عبدالبصير محمد يونس | 2 |
| 2 | يوسف رأفت محمد حماد | 2 |
| 3 | محمد ممدوح عبدالله سليمان | 2 |
| 4 | محمود محسن محمود صبيح | 1 |

---

## Project Introduction

### Project Identification

| Project name: | Course Registration System (CRS) |
|---|---|
| Course: | System Analysis & Design |

### Definition:-
An online system that allows students to register for courses while automatically enforcing prerequisites and credit-hour limits, displaying available seats in real time, and providing registration reports to the administration.

### Objectives:-
* Enable students to register, add, and drop courses online.
* Validate prerequisites and maximum credit hours automatically.
* Display available seats for each section in real time.
* Manage waiting lists for full sections.
* Provide management reports on enrollment per course.
* Send registration confirmation notifications to students.

### Problems Solved:-
* Prerequisite and credit-hour errors caused by manual record checking.
* Long queues at the start of each semester.
* No real-time information on available seats.

---

## System Request–Course Registration System Project

* **Project Sponsor:** Menoufia University, Ministry of Higher Education and Scientific Research
* **Business Need:** The university suffers from human errors during semester course registration periods due to its reliance on manual review of prerequisites and calculation of minimum and maximum credit hours. This project aims to build an automated system that ensures the accurate application of academic regulations, eliminates scheduling conflicts, and reduces the administrative burden on academic advisors. An online system that allows students to register for courses while automatically enforcing prerequisites and credit-hour limits, displaying available seats in real time, and providing registration reports to the administration.
* **Business Requirements:** 
  * Automated Prerequisite Verification: Automatically prevents students from registering for any course without completing the prerequisite.
  * Credit Limits Management: Determines the maximum and minimum credit hours allowed based on GPA and student status (probation, honors, graduation).
  * Schedule Check: Immediately detects any scheduling conflicts between lectures or final exams before schedule confirmation.
* **Business Value:** 
  * Zero Registration Errors: Stops students from taking courses without prerequisites or wrong credit hours.
  * 80% Reduction in Registration Time: Cuts down the average time required for a student to complete course registration from days to just a few minutes.
  * Zero Queue Overhead: Eliminates physical queues and administrative crowding at student affairs and academic guidance offices.
  * Optimized Resource Allocation: Provides real-time capacity tracking for course sections, enabling better hall assignment and faculty load distribution.
  * Enhanced Student Experience: Offers a transparent, fast, and smooth self-service registration process without scheduling or exam conflicts.
  * Reduced Advisor Burnout: Shifts the academic advisor's role from manual paper-checking to strategic academic mentor ship.
  * Data-Driven Decision Making: Delivers accurate enrollment analytics and reporting for administrators to plan future semester offerings.
  * Fair System: Applies college rules equally to all students.
  * Clear Reports: Gives the management fast reports on student numbers per course.
* **Special Issues or Constraints:** 
  * Peak Load & Performance: The system must handle high traffic and hundreds of concurrent users during the registration week without crashing or slowing down.
  * System Availability: The system needs to be available 24/7 during the active registration period.
  * Security & Data Privacy: Student records, grades, and GPA data must be securely protected with proper access controls for students, advisors, and admins.
  * Bylaws Compliance: The rules engine must strictly comply with the university’s credit-hour academic regulations.
  * User Adoption: Academic advisors and administrators must receive basic training on how to handle override requests and manage registration.