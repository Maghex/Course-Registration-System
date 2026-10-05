# System Request — Course Registration System (CRS)

**Project name:** Course Registration System (CRS)
**Course:** System Analysis & Design

---

## 1. Project Sponsor

**Vice Dean for Education and Student Affairs** — initiates the project, approves its budget, and receives its results.

**Business unit supported:** Student Affairs Office (course registration).

---

## 2. Business Need

The faculty has more than 5,000 students. Course registration currently suffers from:

1. **Prerequisite and credit-hour errors:** staff check each student's record by hand, so students are sometimes registered in courses they are not eligible for, or exceed the allowed credit hours.
2. **Long queues and waiting time** at the start of each semester; students lose days to complete registration.
3. **No real-time view of available seats:** students cannot tell whether a section is full until they reach the registration desk.

**The need:** a reliable self-service system that lets students register online while enforcing academic rules automatically.

---

## 3. Business Requirements

The system must provide:

1. **Online registration** from a phone or computer.
2. **Automatic validation** of prerequisites and the maximum credit hours.
3. **Real-time display of available seats** for each section.
4. A **waiting list** when a section is full.
5. **Add and drop** of courses during the registration period.
6. **Management reports** (e.g. number of registered students per course).
7. **Confirmation notifications** to the student.

---

## 4. Business Value

*(Annual estimates, based on 5,000+ students. Assumptions are stated so they can be adjusted.)*

**Tangible benefits**

| Benefit | Estimate (EGP / year) | Assumption |
|---|---:|---|
| Staff time saved | 90,000 | 15 employees × 6 registration weeks × 2,000 EGP/week = 180,000; the system saves ~50% |
| Paper and printing saved | 40,000 | 10,000 registrations per year (5,000 students × 2 semesters) × 4 EGP per form |
| Fewer registration errors | 50,000 | 5% of registrations (500 cases) need manual correction at 100 EGP each |
| **Total** | **≈ 180,000** | |

**Intangible benefits**
- Higher student satisfaction and a faster registration experience.
- Accurate, real-time data to plan sections and teaching staff.
- Transparency and traceability of registration decisions.

---

## 5. Special Issues and Constraints

- **Deadline:** the system must be ready before the next registration period.
- **Peak load:** a large number of students register at the same time on registration day; the system must not crash or sell the same seat twice.
- **Security and privacy:** student data must be protected and accessible by role only.
- **Data migration:** existing student and course data must be transferred from the current system.
- **Different academic rules:** prerequisites and credit limits differ between programs, so they must be configurable rather than fixed in the code.
