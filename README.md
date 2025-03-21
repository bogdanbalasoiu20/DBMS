  Cinema Database Management System (DBMS)
This project represents a Database Management System (DBMS) designed for managing the activities of a cinema. It was developed as part of a university course on relational databases and was implemented using Oracle Database 21c Express Edition.

  Purpose
The database efficiently organizes and manages key information related to the operation of a cinema, such as:

Movie details (title, director, genre, duration, release year, description)
Screening rooms and their capacities
Projections with date, time, and location
Users, their preferences, reviews, bookings, and tickets
This system provides employees with a clear overview of projections, customer activity, and movie popularity, streamlining the cinema's workflow and improving customer experience.

 Structure
The database includes 8 main tables and multiple relationships between them:

FILM, SALA, PROIECTIE, UTILIZATOR, BILET, REZERVARE, RECENZIE, UTILIZATORI_LA_FILM
It enforces relational integrity through primary keys, foreign keys, and includes various constraints and stored procedures.

  Features
Fully normalized database schema with ERD and conceptual diagram
Sample data for all entities (over 50+ entries)
Complex stored procedures using:
PL/SQL collections (associative arrays, nested tables, VARRAYs)
Nested and parameterized cursors
Advanced exception handling
Triggers:
LMD (statement-level and row-level)
LDD (schema-level) with structure monitoring
  Example Use Cases
Automatically update late-night movie showtimes and notify customers
Identify top-rated new movies
Analyze summer reviews for specific films
Generate user statistics for rooms over custom time periods
Prevent unauthorized table deletions
