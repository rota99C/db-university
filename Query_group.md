1) SELECT COUNT(id) 
AS number_signUp,YEAR(enrolment_date) AS enrolment_year 
FROM students 
GROUP BY enrolment_year


2) SELECT COUNT(*) 
AS number_teachers, office_address 
FROM teachers 
GROUP BY office_address


3) SELECT AVG(vote)
AS media_voti, exam_id 
FROM `exam_student` 
GROUP BY exam_id

4) SELECT COUNT(*) 
AS numero_corsi, department_id 
FROM `degrees` 
GROUP BY department_id

