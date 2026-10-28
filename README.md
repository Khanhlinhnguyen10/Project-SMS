# PROJECT: STUDENT MANAGEMENT SYSTEM
> **Course:** Software Engineering  
> **Tech Stack:** Python, MySQL, HTML, CSS, JavaScript  
> **Supported Tools:** Draw.io, SSMS, Visual Studio Code, Figma

---
## PROJECT OVERVIEW
**PROJECT: STUDENT MANAGEMENT SYSTEM** is a comprehensive web-based application designed to support academic and administrative operations for educational institutions. The system provides role-based access control for three main user groups: **Administrator**, **Lecturer**, and **Student**, ensuring streamlined academic operations

---
## KEY FEATURES
### 1. Authentication & Security
* **Role-Based Access Control:** Restricts features and data according to user permissions (Admin, Lecturer, Student).
* **Account Provisioning:** Admins register new accounts with auto-generated Student/Lecturer IDs and default credentials.
* **Session & Security Rules:** Auto-terminates sessions after 15 minutes of inactivity; includes password recovery and complexity-checked password changes

### 2. User Management
* **Student Management:** Admins create, view, update, and delete student records with administrative statuses; students can update their own contact information.
* **Lecturer Management:** Admins manage lecturer profiles and assign them to class sections; lecturers can update their own contact details.

### 3. Academic Management
* **Curriculum Management:** Students view major curricula, compulsory/elective courses, credits, prerequisites, and automated completion status.
* **Semester Management:** Admins configure academic semesters, registration windows, examination timelines, and linked section offerings.
* **Faculty & Course Management:** Admins manage faculties, course catalogs, and class sections (capacity, assigned lecturer, room, and timetable).

### 4. Grading & Attendance Management
* **Attendance Tracking:** Lecturers record daily attendance for assigned sections with automated attendance rate calculations.
* **Gradebook Management:** Record midterms, assignments, and finals with range validation (0.0 to 10.0); automatically calculates weighted final grades and letter grades.
* **GPA & Transcripts:** Automatically computes Semester and Cumulative GPAs; provides students with access to finalized academic transcripts.
