# STUDENTDATABASE-MANAGEMENT-SYSTEM-MY-SQL-

# Student Information Database

This repository contains the SQL table structures for a student information database. The database is designed to store information about students, their courses, and corresponding marks.

## Tables

### 1. student_information

- **Stud_id:** Primary key, unique identifier for each student.
- **Stud_Name:** Student's name.
- **City_State:** City and state where the student resides.
- **Age:** Age of the student.
- **Roll_no:** Roll number assigned to the student.
- **Community:** Community to which the student belongs.
- **Course_ID:** Foreign key linking to the `course_information` table.

### 2. course_information

- **course_id:** Unique identifier for each course.
- **course_name:** Name of the course.

### 3. marks_info

- **marks_id:** Unique identifier for each set of marks.
- **student_id:** Foreign key linking to the `student_information` table.
- **finance:** Marks obtained in the finance subject.
- **cost:** Marks obtained in the cost subject.
- **corporate:** Marks obtained in the corporate subject.

## Data Cleansing

- The database structure includes primary keys and foreign keys to maintain data integrity.
- SQL queries for handling missing values and basic data cleansing are provided in the repository.

## Advanced Analysis

- SQL queries for advanced analyses, such as pass percentage by community, consistent performance, and average age by course, are included.


