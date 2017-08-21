# java-datechooser
This activity introduces JDateChooser being applied to JDBC + SQLite application.

### References
* [JDateChooser from toedter](https://toedter.com/jcalendar/)
* [SQLite Datatypes](https://sqlite.org/datatype3.html)
* [JDBC API](https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/)

### Todos
- [X] Setup and create a sqlite database schema.
  ```sql
	create table profile(
		id int primary key,
		name varchar(50),
		birthday text,
		image blob
	)
  ```
- [X] Design and build an application that will exhibit JDateChooser and Image.
  * Tasks
    - [X] A desktop app that should store basic profile information that includes name, birthday and profile image.
    - [X] A desktop app that should retrieve basic profile information and display using JTable.
    - [X] A desktop app that should update basic profile information.
    - [X] A desktop app that should remove basic profile information.
- [X] Component Checklist
  - [X] JFrame
  - [X] JLabel
  - [X] JButton
  - [X] JTextField
  - [X] JFileChooser
  - [X] JDateChooser
  - [X] JTable

### Submit
```console
TO: cbalaman@uic.edu.ph
SUBJECT: OOP BSIT3-<SECTION> LASTNAME1_LASTNAME2_082217
BODY:
	Write your message/concern here.
	Clean and Build the project and attach Netbeans Project Directory that includes dist folder. 


DUE DATE: August 24, 2017 (11:00 PM)
```

Good Luck! :octocat:
