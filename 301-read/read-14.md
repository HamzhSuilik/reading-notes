# *Database Normalization*
**A way to organize a database by separating large tables into smaller tables in order to avoid duplication**

**Each table in the database should be customized for a specific purpose to make the database more organized and easier to read or modify**

### *Reasons for Normalization*

- **to minimize duplicate data**
- **to minimize or avoid data modification issues**
- **to simplify queries**

**Databases that are not normalized will contain duplicate data and this may lead to data collisions**

**Duplicated information presents two problems**
- **It increases storage and decreases performance.**
- **It becomes more difficult to maintain data changes.**

**There are three common forms of normalization:**

- **First Normal Form** : The information is stored in a relational table
and each column contains atomic values, and there are not repeating groups of columns.
- **Second Normal Form** : The table is in first normal form and all the columns depend on the table’s primary key.
- **Third Normal Form** : The table is in second normal form and all of its columns are not transitively dependent on the primary key.

