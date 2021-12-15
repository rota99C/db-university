1) SELECT students.name, students.surname, students.degree_id 
FROM `students` 
JOIN `degrees` 
ON students.degree_id = degrees.id WHERE degrees.name = "Corso di Laurea in Economia"

2) SELECT degrees.name 
FROM degrees 
JOIN departments 
on degrees.department_id= departments.id WHERE departments.name = "Dipartimento di Neuroscienze"

3) SELECT courses.name 
from courses 
JOIN course_teacher 
on courses.id= course_teacher.course_id where teacher_id=44

4) SELECT students.name, students.surname, students.degree_id, departments.id 
from students 
JOIN degrees 
on students.degree_id= degrees.id 
JOIN departments 
on degrees.department_id = departments.id 
ORDER BY students.surname ASC

