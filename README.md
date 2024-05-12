COMMANDS: 
SQL> Grant Create session to student; 
 SQL> Grant create table to student;  
SQL> Connect student/young; 
SQL> Connect system/managers; 
SQL> Create user staff identified by guru; 
 SQL> Grant resource to staff; 
SQL> Connect staff/guru;  
SQL> Select * from staff; 
Staff master in a table in the user staff we first log on the staff [SQL> Connect staff/guru;] 
SQL> Grant select insert on staff master to student; 
Now log on to student and try the select command  
SQL> Connect student/young; 
SQL> Select * from staff; 
          SQL> Grant select, update, delete on student-master to staff;. 
SQL> REVOKE SELECT, INSERT ON STUDENT_MASTER from staff; 
SQL> REVOKE SELECT ON STUDENT_MASTER from rajan; 
 
 
 
