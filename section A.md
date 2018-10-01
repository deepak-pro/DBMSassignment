### DDL COMMANDS 
---

1. *CREATE  TABLE*

```   create table student ( name varchar(10),id char (5),course varchar (6),college varchar (8));``` 

2. *ALTER TABLE* 
   
   To add new column- 
   
  ```alter table student add( age number (2));```

   To making changes in the column -
   
   ```alter table student modify ( name varchar2 (10));```

3. *DROP TABLE*

   To delete a column-
   
   ```alter table student drop name;```  

4. *RENAME*

   To rename the name of the table-
    
    ```rename student to stud_iips;```

5. *TRUNCATE*

   ```Truncate  table student ;```  

---
### DML COMMANDS
---

1. *INSERT INTO*

   ```insert into student values ( 'ramesh','DS01','MCA','IIPS');``` 

2. *SELECT*
   
   To view the whole table-
   
   ```select * from student ;``` 

   To view the specific column of the table-
   
   ```select name,id,course,college  from student ;``` 
 
   To view the particular data of the table-
   
   ```select name ,id from student
    where name='suresh';```
           
    It will show you the distinct values of colleges-
    
    ```select distinct college from student ;```

3. *UPDATE* 

     To update the  data in the table-
     
     ```update student set name='rajesh'
      where name='ramesh';```                 

4. *DELETE*

   To delete particular data from the particular column of the table
  
   ```delete from student 
      where name='suresh';```      
