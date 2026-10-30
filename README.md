# Esports Tournament Management System

ISTE 330 Database Connectivity and Access - Group 1

| Member | RIT ID | Role |
|---|---|---|
| Ravindran, Dhruva | dsr1378 | Project Lead and Documentation |
| Ziyaev, Abdullojon | za9369 | Database Architect |
| Nathershah, Faizahnadir | fn6379 | Database Logic and Sample Data |
| Naseem, Abdullah | afn5363 | Java Back-End (JDBC) |
| Poojary, Swati | sp6056 | Java Front-End, Reports and Testing |

## Milestone 1 (due Fri 30 Oct 2026)

| Item | Location |
|---|---|
| Milestone 1 document (PDF, the version to submit) | `docs/milestone1/ISTE330_Group1_Milestone1.pdf` |
| Milestone 1 document (editable Word version) | `docs/milestone1/ISTE330_Group1_Milestone1.docx` |
| ERD, UML and Gantt images | `docs/milestone1/diagrams/` |
| Diagram source files and GanttProject file | `docs/milestone1/source/` |

The GanttProject file (`Project_Schedule.gan`) opens in GanttProject (ganttproject.biz). The `.dot` files are the Graphviz sources used to draw the diagrams.

## Coming in Milestone 2 (due Wed 18 Nov 2026)

- `database/` - the SQL script that creates the database, tables, keys, stored procedures and sample data
- `src/` - the Java source code (JDBC connection, login with hashed passwords, CRUD, reports)
- Test login accounts for the Director, Coach and Player roles

## Software

- MySQL 9.7 (the team's development version)
- Java and the MySQL JDBC driver versions will be listed here in Milestone 2

## Team rules

- One branch per milestone (`Milestone-1`, `Milestone-2`, `Milestone-3`). `main` holds only submitted versions.
- The Database Architect owns the SQL script, so there is only ever one version of the database.
- Changes to tables or columns are agreed by the group first, because they affect the Java code.
- A feature counts as done only when it runs on a second member's computer.

The full README with launch instructions will be completed for Milestone 3.
