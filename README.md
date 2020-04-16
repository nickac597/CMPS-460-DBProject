# CMPS-460-DBProject
Project for DBMS CMPS-460 to create a functional database website/application

# Specifications
Database Project Proposal
Database Application for University of Fakeland, by Nicholas Bourgeois (c00222259), Nicholas Catalano (c00117296)

A University in Fakeland by the name of University of Fakeland. The university keeps track of it's students and also it's faculty and deals with various data regarding these individuals. We want to design and implement a database in order to provide a place to store the identification, and grades of students, as well as classes and other data for professors. There will also be a database listing all courses offered by the university

The University has 3 colleges, the College of Science, the College of Mathematics, and the College of Computer Science. Each professor belongs to a single college, but may be an instructor for multiple classes. Meanwhile, students may also be a part of a single college, as well as participating in multiple classes

Students grades are recorded in a database, as well as their GPA and 10 digit ID number (UFID). Students are also given a classification for their year, a number of credit hours for the current semester, as well as their total credit hours and major. Finally, students have contact information such as a phone number and personal email.

Professors meanwhile, also have UFIDs alongside their salaries, and the number of years working at the university. Alongside this, professors are given a number representing how many classes they are instructing, alongside the course ID for the courses they are instructing. Finally, they also have a phone number, and personal email address.

The university course database will offer an overview of all courses, including each course's ID, section number, number of students enrolled in the class, the subject for the course, the maximum capacity of the class, professor instructing the course, as well as the meeting time of the course

The following interactions and more are expected from the database system:

1. The number of students enrolled in a particular class
3. Professors that have been instructing for more than 5 years
4. Name and UFIDs of all students enrolled in a particular class
5. Name and UFIDs of all professors within a given college
6. All professors instructing more than 2 classes
7. Updating the number of credit hours total for a given student
8. Reports for professors showing the students whose GPAs are lower than a 2.5
9. Show all courses for a given subject
10. Show all classes where spots are still open
