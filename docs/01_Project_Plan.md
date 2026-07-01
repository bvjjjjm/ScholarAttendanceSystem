# Scholar Event Management System (SEMS)

## Project Plan

Version: 1.0

Prepared by:
Vladdimer Jr. E. Boteros

Date:
July 2026

---

# Table of Contents

1. Project Overview
2. Background
3. Problem Statement
4. Proposed Solution
5. Vision
6. Mission
7. Goals
8. Objectives
9. Scope
10. Out of Scope
11. Stakeholders
12. User Roles
13. Functional Modules
14. Technology Stack
15. System Architecture
16. Development Methodology
17. Development Phases
18. Timeline
19. Risk Assessment
20. Success Metrics
21. Future Enhancements
22. Conclusion



1. Project Overview
The Scholar Event Management System (SEMS) is a web-based application designed to streamline the management of scholar events through secure QR code attendance, centralized event administration, real-time analytics, and automated reporting. The system replaces manual attendance recording with a faster, more accurate, and secure digital solution while providing administrators with valuable insights into scholar participation.

2. Background
Scholar events are often managed using paper attendance sheets or spreadsheets, resulting in long queues, duplicate records, inaccurate attendance, and time-consuming report generation. These manual processes reduce efficiency and make it difficult to monitor scholar participation over time.

3. Problem Statement
Current attendance process suffers from:

-Manual attendance recording
-Long registration queues
-Human errors
-Duplicate attendance
-Lost records
-Slow report generation
-No centralized attendance history
-Lack of real-time monitoring

4. Proposed Solution
The proposed solution is the Scholar Event Management System (SEMS), which uses QR code technology to automate attendance recording. The system provides centralized scholar management, event management, attendance monitoring, analytics, reporting, and administrative tools within a secure web-based platform.

5. Vision
To become a reliable and secure digital platform that modernizes scholar event management through automation, accurate attendance tracking, and data-driven decision-making.

6. Mission
To provide administrators and event staff with an efficient, user-friendly, and secure system that simplifies scholar event management while improving attendance accuracy and operational efficiency.

7. Goals
-Digitize attendance
-Eliminate paper attendance sheets
-Improve attendance accuracy
-Reduce registration time
-Generate reports automatically
-Improve event management

8. Objectives
-Record attendance within 2 seconds after scanning.
-Prevent duplicate attendance.
-Generate reports in under 10 seconds.
-Support 500+ scholars per event.
-Reduce attendance processing time by at least 80%.

9. Scope
-Scholar Management
-Event Management
-QR Attendance
-Dashboard
-Calendar
-Reports
-User Management
-Notifications
-Data Export

10. Out of Scope
-Online payments
-Scholarship application processing
-Student grading
-Learning management
-Email marketing
-Financial management

11. Stakeholders
        Stakeholder	            Responsibility
        Scholarship Office	    System owner
        Administrator	        Manage system
        Event Staff	            Record attendance
        Scholars	            Attend events

12. User Roles
Super Admin
-Manage system
-Manage users
-View reports
Administrator
-Manage scholars
-Manage events
-Generate reports
Event Staff
-Scan attendance
-View attendance

13. Functional Modules

Authentication
-----------------
Secure login
Password management
JWT
Scholar Management
------------------
CRUD
Import Excel
Search
Archive
Event Management
------------------
Create
Edit
Close
Archive
QR Attendance
------------------
Scan
Validate
Save
Prevent duplicates
Reports
------------------
PDF
Excel
CSV
Dashboard
------------------
Charts
Statistics
Recent Activity

14. Technology Stack
        Category	        Technology
        Frontend	        Next.js
        Backend	            NestJS
        Database	        PostgreSQL
        ORM	                Prisma
        Authentication	    JWT
        Styling	            Tailwind CSS
        Deployment	        Vercel
        Storage         	PostgreSQL

15. System Architecture
Frontend

↓

REST API

↓

Backend

↓

Database
