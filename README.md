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
- [X] Setup and create a sqlite database schema.