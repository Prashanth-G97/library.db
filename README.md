# library.db

Authors: Stores author information (author_id, author_name, country).

Books: Stores book details (book_id, title, publication_year, author_id).

A one-to-many relationship is established between Authors and Books using author_id as a foreign key, linking books to their respective authors.

The project demonstrates:

Creating tables with primary and foreign keys.

Inserting sample data into these tables.

Updating existing data.

Deleting data, with an emphasis on handling foreign key constraints (e.g., deleting a book before deleting its author).
