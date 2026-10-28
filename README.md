# Esports Tournament Management System

ISTE 330 Database Connectivity and Access - Group 1

| Member | RIT ID | Role |
|---|---|---|
| Ravindran, Dhruva | dsr1378 | Project Lead and Documentation |
| Ziyaev, Abdullojon | za9369 | Database Architect |
| Musaeva, Safiia | sm5383 | Database Logic and Sample Data |
| Naseem, Abdullah | afn5363 | Java Back-End (JDBC) |
| Poojary, Swati | sp6056 | Java Front-End, Reports and Testing |

## Current status: Milestone 1 (due Fri 30 Oct 2026)

| Item | Location |
|---|---|
| Milestone 1 document (submit the PDF) | `docs/milestone1/ISTE330_Group1_Milestone1.pdf` |
| ERD, UML, Gantt images | `docs/milestone1/diagrams/` |
| Diagram sources and GanttProject file | `docs/milestone1/source/` |
| Database script (draft, tested on MySQL 9.7) | `database/esports_tms_setup.sql` |

## Try the database now

1. Open MySQL Workbench.
2. File > Open SQL Script > `database/esports_tms_setup.sql`.
3. Click the lightning bolt to run the whole script. It creates the `esports_tms` database with all tables, views, stored procedures and sample data.

Test logins stored in the database (passwords are hashed, never plain text):

| Role | Username | Password |
|---|---|---|
| Tournament Director | director1 | Director@123 |
| Coach | coach1 | Coach@123 |
| Player | player1 | Player@123 |

## Team rules

- One branch per milestone (`Milestone-1`, `Milestone-2`, `Milestone-3`). `main` holds only submitted, working versions.
- Only the Database Architect edits `database/esports_tms_setup.sql`. Send changes to them.
- Schema freeze on 4 November.
- Nothing is done until it runs on a second member's laptop from a fresh database.

The full README with launch instructions will be completed for Milestone 3.
