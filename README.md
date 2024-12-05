Student Enrollment Management System
This project is a Student Enrollment Management System designed to streamline the process of managing students, courses, teachers, and enrollments. It allows administrators, teachers, and students to interact with the system to manage educational workflows efficiently.

System Overview
The Student Enrollment Management System provides functionalities to:

Add, remove, and manage students, courses, and teachers.
Register students for courses and assign grades.
Allow students to view and manage their course registrations.
Key Entities and Responsibilities

1. Student
Attributes:
studentID: Unique identifier for each student.
name, email, phone, age: Contact details of the student.
Functions:
registerCourse(): Register for a course.
viewCourse(): View enrolled courses.
dropCourse(): Drop a course.

2. Course
Attributes:
courseID: Unique identifier for each course.
courseName, description, credit: Course details.
Functions:
addStudent(): Add a student to the course.
removeStudent(): Remove a student from the course.

3. Teacher
Attributes:
teacherID: Unique identifier for each teacher.
name, department: Information about the teacher.
Functions:
assignCourse(): Assign courses to teachers.

4. Enrollment
Attributes:
enrollmentID: Unique identifier for the enrollment.
dateEnrolled: Date of enrollment.
grade: Assigned grade for the course.
Functions:
assignGrade(): Assign a grade to a student.

5. Admin
Attributes:
adminID: Unique identifier for the admin.
name: Admin’s name.
Functions:
addStudent(), removeStudent(): Manage students.
addCourse(), removeCourse(): Manage courses.
manageEnrollment(): Oversee enrollments.


Features
Student Management: Add, update, and remove student records.
Course Management: Create and modify course details.
Teacher Management: Assign courses to teachers.
Enrollment Tracking: Track which students are enrolled in which courses.
Grade Assignment: Record and manage grades for students.

## Contributors
M.D.J.Kavishan Nipun Shantha - 22ug1-0704