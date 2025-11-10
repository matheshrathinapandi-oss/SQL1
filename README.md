
# ANTI JOIN:
An ANTI JOIN returns rows that do not have matching records in the other table.
# FULL ANTI JOIN 
<img width="1129" height="900" alt="image" src="https://github.com/user-attachments/assets/6fd41091-223f-4d1c-84bf-56701d04dc8e" />

# DATE FUNCTIONS:
Find the employee who joined before 2004

<img width="437" height="218" alt="Screenshot 2025-11-04 185001" src="https://github.com/user-attachments/assets/45928f95-4824-42fa-915c-c04670cb65b7" />

Find the employee who joined previous month

<img width="495" height="203" alt="Screenshot 2025-11-04 185322" src="https://github.com/user-attachments/assets/c3a67a49-9ecd-4edb-85a4-1b35e7bb9732" />

Find month-wise employees

<img width="557" height="306" alt="Screenshot 2025-11-04 185530" src="https://github.com/user-attachments/assets/fa110e78-c054-45c2-b0be-d2274655deb8" />

Find employees who have more than five years experience

<img width="525" height="293" alt="Screenshot 2025-11-04 185642" src="https://github.com/user-attachments/assets/43c665ce-7892-41cf-b613-30d9bc6095c6" />

Find the age for all employees

<img width="565" height="347" alt="Screenshot 2025-11-04 185838" src="https://github.com/user-attachments/assets/baf783f1-17ef-4c51-9a22-8f69e5a1a34b" />

Find the employees who have today birthday  

<img width="699" height="206" alt="Screenshot 2025-11-04 190222" src="https://github.com/user-attachments/assets/3953953f-24f7-460d-b8e9-0579e0b77992" />

# Normalization:
Normalization is the process of organizing data in a database to Reduce redundancy (duplicate data).Improve data integrity.Make updates, inserts, and deletes efficient
It divides a large table into smaller related tables and links them using foreign keys.

| StudentID | StudentName | Course       | Instructor    | InstructorPhone        |
| --------- | ----------- | ------------ | ------------- | ---------------------- |
| 1         | Ravi        | DBMS, Python | Anitha, Kumar | 9876543210, 9876501234 |
| 2         | Meena       | Java         | Kumar         | 9876501234             |
| 3         | Arjun       | DBMS, Java   | Anitha, Kumar | 9876543210, 9876501234 |

# 1NF:
All attributes must have atomic (single) values — no repeating or multivalued fields.
| StudentID | StudentName | Course | Instructor | InstructorPhone |
| --------- | ----------- | ------ | ---------- | --------------- |
| 1         | Ravi        | DBMS   | Anitha     | 9876543210      |
| 1         | Ravi        | Python | Kumar      | 9876501234      |
| 2         | Meena       | Java   | Kumar      | 9876501234      |
| 3         | Arjun       | DBMS   | Anitha     | 9876543210      |
| 3         | Arjun       | Java   | Kumar      | 9876501234      |
# 2NF:

* Table must be in 1NF
* All non-key attributes must depend on the entire primary key, not part of it.
  
| StudentID | StudentName | Course |
| --------- | ----------- | ------ |
| 1         | Ravi        | DBMS   |
| 1         | Ravi        | Python |
| 2         | Meena       | Java   |
| 3         | Arjun       | DBMS   |
| 3         | Arjun       | Java   |

| Course | Instructor | InstructorPhone |
| ------ | ---------- | --------------- |
| DBMS   | Anitha     | 9876543210      |
| Python | Kumar      | 9876501234      |
| Java   | Kumar      | 9876501234      |

# 3NF:

* Table must be in 2NF
*  No transitive dependency (non-key depends on another non-key)
  
| StudentID | StudentName | Course |
| --------- | ----------- | ------ |
| 1         | Ravi        | DBMS   |
| 1         | Ravi        | Python |
| 2         | Meena       | Java   |
| 3         | Arjun       | DBMS   |
| 3         | Arjun       | Java   |

| Course | Instructor |
| ------ | ---------- |
| DBMS   | Anitha     |
| Python | Kumar      |
| Java   | Kumar      |

| Instructor | InstructorPhone |
| ---------- | --------------- |
| Anitha     | 9876543210      |
| Kumar      | 9876501234      |

print department wise highest salary

<img width="632" height="317" alt="Screenshot 2025-11-05 183019" src="https://github.com/user-attachments/assets/12217f23-7f7b-496f-8397-a80f7701eb9e" />

print the second highest salary for each department

<img width="615" height="267" alt="Screenshot 2025-11-06 102503" src="https://github.com/user-attachments/assets/6c61c355-daba-4fe8-bfed-cc94c131b473" />

print department which have more than one employee

<img width="456" height="267" alt="Screenshot 2025-11-05 183304" src="https://github.com/user-attachments/assets/93abad44-d949-49c4-afa2-2b6233c63b4c" />

Print the customer who orderd more than two products

<img width="511" height="225" alt="Screenshot 2025-11-07 104351" src="https://github.com/user-attachments/assets/5b714d0b-4bc0-41ab-9a21-19466129edd2" />

SQL Hcakerrank problems

<img width="1833" height="855" alt="Screenshot 2025-11-07 104748" src="https://github.com/user-attachments/assets/e1f32e1d-7f3b-4904-b5d7-67f79917c356" />

Example program for inheritance

<img width="651" height="740" alt="Screenshot 2025-11-06 104838" src="https://github.com/user-attachments/assets/cc3a0af6-d5a5-4262-92f4-6102412d83c3" />

write a program for encapsulation

<img width="769" height="851" alt="Screenshot 2025-11-05 185226" src="https://github.com/user-attachments/assets/42bc8b50-b5ed-4ba8-8c20-d45f54d59f11" />

Write a program for generators

<img width="656" height="869" alt="Screenshot 2025-11-06 185656" src="https://github.com/user-attachments/assets/a9c712d2-3d3c-4878-9888-8b8b0630858a" />

Leet code problems

<img width="1674" height="831" alt="Screenshot 2025-11-10 104839" src="https://github.com/user-attachments/assets/bd2fdd5b-42e1-49ba-922c-18310ec070c5" />

<img width="1747" height="837" alt="Screenshot 2025-11-10 104614" src="https://github.com/user-attachments/assets/a1f7e98c-65a2-4f06-b310-9512dd890daf" />

<img width="1627" height="823" alt="Screenshot 2025-11-10 105914" src="https://github.com/user-attachments/assets/8b798603-3b66-4cdd-b82a-14febb0c7b9b" />

<img width="1698" height="859" alt="Screenshot 2025-11-10 182502" src="https://github.com/user-attachments/assets/47f1f025-9af0-4f24-a530-c6a732b78f92" />

