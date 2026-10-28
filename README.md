# 🎓 PROJECT: STUDENT MANAGEMENT SYSTEM
> **Course:** Software Engineering  
> **Tech Stack:** Python, MySQL, HTML, CSS, JavaScript  
> **Supported Tools:** Draw.io, SSMS, Visual Studio Code, Figma

---
## 📌 PROJECT OVERVIEW
**STUDENT MANAGEMENT SYSTEM** is a comprehensive web-based application designed to support academic and administrative operations for educational institutions. The system provides role-based access control for three main user groups: **Administrator**, **Lecturer**, and **Student**, ensuring streamlined academic operations

---
## ✨ MAIN FEATURES
### 🔑 1. Authentication & Authorization
* **Registration:** Admins create student and lecturer accounts based on official records with required validation, default credentials, and auto-generated IDs.
* **Log in:** Authenticates registered users via username and password, identifying roles to display corresponding permitted functions and handling account lock errors.
* **Log out:** Terminates active user sessions at any time and clears all temporary session data.
* **Password Change:** Allows students and lecturers to update passwords with current credential verification and complexity compliance.
* **Password Recovery:** Enables account recovery via registered email or phone number after verifying account ownership.

### 👤 2. User Management
* **Student Management:** Admins manage student records with administrative statuses; students can view and update their own contact information while restricting edits to identification data.
* **Lecturer Management:** Admins create and manage lecturer profiles and section assignments; lecturers can view and update their own contact details.

### 📚 3. Academic Management
* **Curriculum Management:** Students view major curricula, compulsory and elective courses, credits, prerequisites, and automated completion status tracking.
* **Semester Management:** Admins configure academic semesters, timelines, course registration windows, and examination schedules.
* **Faculty Management:** Admins manage faculty records (Faculty Code, Name, Email, Phone) with safety restrictions against deleting faculties linked to active courses or enrolled students.
* **Course Management:** Admins manage the course catalog (Course Code, Name, Credits, Managing Faculty, Prerequisites) with protection against deleting active or historical courses.
* **Class Section Management:** Admins manage class sections per semester, including Class Code, assigned lecturer, maximum capacity, current enrollment, room, and schedules.

### 📊 4. Grading & Attendance Management
* **Attendance Management:** Lecturers record daily attendance for assigned active sections with automatic attendance rate calculations.
* **Gradebook Management:** Lecturers record midterm, assignment, attendance, and final exam marks (validated 0.0–10.0) to compute weighted final course grades and letter grades.
* **GPA Calculation:** Automatically calculates Semester GPA and Cumulative GPA based on finalized academic results and credit-weighted rules.
* **Academic Transcript Viewing:** Allows students to view finalized component marks, exam results, letter grades, and updated GPA history.
