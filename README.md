### README for Kata 5: Email Storage with SQLite

# Kata 5: Email Storage with SQLite

## Problem Description

This kata focuses on processing a list of email addresses and storing them in a SQLite database. The program reads email addresses from a file, validates the format, and inserts them into a database table. If the table does not exist, it is created dynamically.

This exercise highlights database interactions, file processing, and basic data validation in Java.

---

## Functionalities

1. **Database Management**  
   - Connects to a SQLite database (`Kata5-PRUEBA.DB`).  
   - Creates a table named `MAILS` if it does not already exist.

2. **File Reading**  
   - Reads email addresses from a text file (`emails.txt`).  

3. **Data Validation and Storage**  
   - Validates email addresses to ensure they contain the `@` character.  
   - Inserts valid email addresses into the `MAILS` table.  

4. **Logging**  
   - Displays the number of email records successfully inserted.

---

## Scope

This project demonstrates:
- **Database Integration**: Basic use of SQLite in Java for data persistence.  
- **File Processing**: Reading and validating data from text files.  
- **SQL Queries**: Executing SQL commands dynamically within a Java application.  
- **Data Validation**: Simple validation to ensure valid email formats.

---

### Tags

Possible tags for this project:  
- `#java-sql`  
- `#file-processing`  
- `#data-storage`  
- `#sqlite`
