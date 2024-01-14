This presentation, created for the project defense of the Oracle 'Database Design and Programming with SQL' course, serves as an example of a school system database.

Content includes:

- School system Entity-Relationship Diagram (ERD).
- CRUD operations.
- Data Definition Language (DDL) statements.

Key considerations:

- The Student-Guardian relationship is represented as a Many-to-Many (M:N) association using the join table 'student_guardian.'
- A similar approach is applied to the Student-Class relationship, utilizing the 'student_class' join table.
- The Professor table incorporates a recursive join, allowing a professor to also serve as a headmaster, for instance.

Query example:
- The fourth query demonstrates a join between 't1_table' (teacher) and 't2_table' (subject), followed by a repeated process with 't3_table' (classroom). This approach allows joining from three to n tables, following the formula n-1, indicating one join for any two tables, two joins for three tables, and so on.

Reminder:

- The syntax column_name1 || ' ' || column_name2 is specific to Oracle systems.
