# java-datechooser
This activity introduces JDateChooser and be applied in JDBC + SQLite application.

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
  > Tasks
  * A desktop app that should store basic profile information that includes name, birthday and profile image.
  * A desktop app that should retrieve basic profile information and display using JTable.
  * A desktop app that should update basic profile information.
  * A desktop app that should remove basic profile information.
- [X] Component Checklist
  - [X] JFrame
  - [X] JLabel
  - [X] JButton
  - [X] JTextField
  - [X] JFileChooser
  - [X] JDateChooser
  - [X] JTable
