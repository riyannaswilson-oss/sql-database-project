# Happy Learning Kindergarten Database

## Overview
A database design project completed for IT 214 at George Mason University. The project models a fictional kindergarten, including students, parents, teachers, and classes.

## Database Entities
- CLASS_RW: Classroom information and assigned teachers.
- STUDENT_RW: Student information and class assignments.
- PARENT_RW: Parent contact information.
- TEACHER_RW: Teacher information and qualifications.
- STUDENT_PARENT_RW: Connects students and parents.

## Relationships
- One teacher can teach multiple classes.
- One class can contain multiple students.
- Students and parents have a many-to-many relationship through a bridge table.

## Tools
- MySQL Workbench
- Entity-relationship diagrams (ERDs)

## Skills Demonstrated
- Relational database design
- Primary and foreign keys
- Entity relationships and cardinality
- Bridge tables and composite primary keys
- Database attributes and data types

## Course
IT 214 — George Mason University
