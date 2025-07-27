# Oracle-SQL-Programming-Lab-Reports
This repository contains a series of lab reports (Travaux Pratiques) written in French, focused on practicing database programming and administration using Oracle SQL, SQL*Plus, and PL/SQL triggers. Each report provides hands-on experience to build and reinforce database management concepts.

## 📁 Content Overview


### 📄 TP\_Num1

**Title: Schema Design, Data Insertion & SQL Queries**

This report covers:

* User creation and privilege assignment.
* Schema definition with 5 relational tables and constraints.
* Data insertion using `INSERT INTO`.
* Attribute renaming and column size modification.
* Index creation (primary and secondary).
* Querying metadata (catalogs, constraints, indexes).
* SQL queries for analysis: COVID cases, biologist activity, patient age.
* Use of views for query simplification.

### 📄 TP\_Num2

**Title: Tablespaces, Users, Constraints & SQL Queries**

This report covers:

* Creation of custom tablespaces (`IOT_TBS`, `IOT_TempTBS`).
* Creating and configuring an Oracle user (`C##dbaiot`).
* Granting privileges using `GRANT ALL`.
* Creating relational tables with integrity constraints: `USERS`, `SERVICE`, `THING`, `SUBSCRIBE`.
* Performing DDL operations (adding, dropping, renaming columns).
* Inserting sample records into the tables.
* Writing SQL queries to extract specific information (joins, aggregations, filtering).
* Managing constraints and using system date fields for subscriptions.

---

### 📄 TP\_Num4

**Title: View Creation, Manipulation & Constraint Behavior**

This report explores:

* Logging into SQL\*Plus and creating a new user.
* Executing a script that includes multiple SQL statements.
* Creating and displaying basic views (`ListeBiologistes`, `ListeNomsBiologistes`) and aggregated views (`PreBiologiste`, `VBiologiste`).
* Studying the dynamic nature of views during insert, delete, and update operations.
* Understanding limitations of operations on views due to constraints.
* Creating tables from existing tables (`Effectuerprelev2`) and analyzing constraint differences.
* Advanced SQL queries through joins and views.
* Behavior of views containing aggregation functions (`COUNT`, `GROUP BY`).

---

### 📄 TP\_Num7

**Title: PL/SQL Triggers**

This report focuses on PL/SQL trigger programming:

* `AFTER INSERT`, `AFTER DELETE`, `AFTER UPDATE` triggers for logging changes on the `USERS` table.
* A multi-event trigger on the `THING` table to log additions, updates, and deletions.
* A `BEFORE UPDATE` trigger that checks whether a new `iduser` value exists before allowing an update.
* Managing an `NbThing` field in the `USERS` table using triggers:
  * `NbThing_trigger`: updates the object count after insertion.
  * `NbThingUpdate_trigger`: updates the object count after transferring an object to another user.
* Execution tests and validation of trigger effects.

---

## 👩‍💻 Author

* **Ferchichi Manel**

---

## 🛠️ Technologies Used

* **Oracle SQL & PL/SQL**
* **SQL\*Plus / Oracle SQL Developer**
* **Triggers (AFTER, BEFORE)**
* **SQL commands: DDL, DML, DCL**
* **Views, Constraints, Aggregation Functions**

