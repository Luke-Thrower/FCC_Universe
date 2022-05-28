# FCC_Universe
Freecodecamp universe SQL database

This was a SQL database created in VisualStudioCode and PostgreSQL.

The aim was to test out my SQL skills and build a simple database from scratch to a particular set of standards.

These were: 

Your database should have at least five tables - Tables named galaxy, star, planet, and moon (plus one other)

Each table should have a primary key, which automatically increments and at least one column from each table should be UNIQUE. 

Each primary key column should follow the naming convention table_name_id. For example, the moon table should have a primary key column named moon_id.

Each foreign key column should have the same name as the column it is referencing.

Each table should have a name column and should be of type VARCHAR, use the INT data type for at least two columns that are not a primary or foreign key, and use the NUMERIC, TEXT and BOOLEAN data types at least once.

Each "star" should have a foreign key that references one of the rows in galaxy. Each "planet" should have a foreign key that references one of the rows in star and each "moon" should have a foreign key that references one of the rows on planet.

Each table should have at least three rows and at least three columns - The galaxy, star, planet, and moon tables should each have at least five columns

The galaxy and star tables should each have at least six rows, the planet table should have at least 12 rows, and The moon table should have at least 20 rows

At least two columns per table should not accept NULL values
