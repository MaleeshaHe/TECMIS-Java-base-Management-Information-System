# Group 03 - Management-Information-System-ICT2132-Mini-Project

Management Information System - ICT2132 Mini Project

GUI of this project 


<img src="https://user-images.githubusercontent.com/91375598/223187087-cca932be-791c-47cb-a14a-425cc81067d6.png"  width="450">
<img src="https://user-images.githubusercontent.com/91375598/224529194-e6e40af6-cebc-444c-a83f-7ff7cfc229cc.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223831177-7e3bd25c-7968-429a-b1fe-03f81cfcc157.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223831250-07ca0dd5-cb66-46da-9efe-1107ed2ccbb5.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223831285-338a0bd2-68c4-4ccd-9172-e2a9a113fc73.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223187167-456c2834-37bf-4cc4-a6ee-a9f532f3c630.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223187217-0af46716-ece5-4595-9d5b-029b0e2f729d.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223187255-139cb238-7661-4c6d-bb05-0795096c9db0.png"  width="600">
<img src="https://user-images.githubusercontent.com/91375598/223455277-c09d9cd4-f829-4ef0-90dc-6cbd2d166795.png"  width="600">


# ICT2132 – Object Oriented Programming Practicum - Mini Project

### University of Ruhuna - Faculty of Technology

**Course Unit:** ICT2132 – Object Oriented Programming Practicum  
**Submission Date:** 19th March 2023, 11:00 p.m.

## Project Description

This project is a Java and MySQL-based application developed to manage academic and administrative tasks for the Faculty of Technology. It includes user profile management, course details, student marks and attendance, notices, timetables, and medical records for different user roles (Admin, Lecturer, Student, Technical Officer).

## Features

The system provides specific functionalities for four user roles:

### Admin
- Manage user profiles for Admin, Lecturer, Student, and Technical Officer.
- Create and maintain course details, notices, and timetables.

### Lecturer
- Update personal profile (excluding username and password).
- Manage course materials and upload marks for exams.
- Access student information, eligibility, grades, GPA, attendance, and medical records.
- View notices.

### Technical Officer
- Update personal profile (excluding username and password).
- Maintain attendance and medical records of students.
- View notices and department timetables.

### Student
- Update contact details and profile picture.
- View attendance, medical records, course details, grades, GPA, timetables, and notices.

## Database Requirements

- **Users:** 1 Admin, at least 4 Lecturers, 2 Technical Officers, and 10 Students.
- **Attendance Records:** For 6 subjects with different attendance scenarios.
  - Subject ICT01 is theory-only, while other subjects include theory and practical sessions.
  - Attendance records should cover cases with >=80%, <80%, and medical exemptions.

## Course and Assessment Details

### Subjects and Mark Distribution

| Subject Code | Assessments                 | Midterm | Final Theory | Final Practical |
|--------------|-----------------------------|---------|--------------|-----------------|
| ICT01        | 10% (2 of 3 quizzes)        | 20%     | 40%          | 30%            |
| ICT02        | 10% (3 of 4 quizzes)        | 10%     | 20%          | 60%            |
| ICT03        | 10% (2 of 3 quizzes)        | 20%     | 40%          | 30%            |
| ICT04        | 10% (2 of 3 quizzes)        | 20%     | 30%          | 40%            |

- **Eligibility Criteria:** Continuous Assessment (CA) must be ≥ 50% for final exam eligibility.
- **Grade Viewing:** View eligibility status, final marks, grades, SGPA, and CGPA for individual students and the entire batch.

## System Requirements

- **Programming Language:** Java
- **Database:** MySQL

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/ICT2132-OOP-Mini-Project.git
   cd ICT2132-OOP-Mini-Project
   ```

2. **Database Setup:**
   - Install MySQL and create a new database.
   - Import the provided SQL file (located in `/database/ict2132_schema.sql`) to initialize tables.

3. **Configure Database Connection:**
   - Update database connection details in `src/config/DatabaseConfig.java`.

4. **Run the Application:**
   - Open the project in your Java IDE (e.g., IntelliJ, Eclipse).
   - Build and run the application.

## Usage

1. **Login:** Use predefined credentials for Admin, Lecturer, Technical Officer, or Student roles.
2. **Manage Data:** Admin can create and modify user profiles, courses, notices, and timetables.
3. **Student Records:** Add and view attendance, marks, and medical records.
4. **Assessment and Grades:** Calculate and display student eligibility, CA scores, final grades, SGPA, and CGPA.

## Project Structure

- **src**: Contains all source code files.
- **database**: Contains database schema and SQL scripts.
- **docs**: Project documentation and additional resources.

## Demo

Watch a video demonstration of the project [here](https://youtu.be/fPd2eKRtsBI?si=-iwhqnltF48Xma1A).

Or click the image below to watch:

[![Project Demo](https://img.youtube.com/vi/fPd2eKRtsBI/0.jpg)](https://youtu.be/fPd2eKRtsBI?si=-iwhqnltF48Xma1A)

## License

This project is for educational purposes under the course unit ICT2132 – Object Oriented Programming Practicum. It is not intended for commercial use.
```

This complete README includes all the project information, setup steps, and usage instructions along with the embedded video demo link and thumbnail. Adjust any details specific to your project repository or setup as needed. Let me know if there are additional elements you'd like to add!


