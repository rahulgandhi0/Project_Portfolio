**Project: Co-Actor Network Construction and Advanced Movie Database Analytics Using TMDb API and SQLite**
The project involves two tasks:

**Build a Co-Actor Network:**

Use the TMDb API to collect data on actors and their co-actors from highly rated movies.
Represent this data as a graph, with nodes (actors) and edges (co-actor relationships).
Export the graph data into CSV files (nodes.csv and edges.csv).

**Database Analysis with SQLite:**

Create, partition, and query an SQLite database using movie and cast data.
Answer specific analytical questions using SQL, such as identifying top actors, high-scoring movies, and collaborative relationships.

**Tools, Technologies, and Skills:
Languages and Libraries:
**
Python 3.10.x (with the Standard Library and Requests for API interaction).
SQLite 3.37.2 (for database creation and querying).
Skills:

API integration and data extraction (TMDb API).
Data modeling and graph construction.
CSV manipulation.
SQL for database creation, indexing, querying, and Full-Text Search (FTS).
Data visualization and interpretation (via graph analysis).
Tasks Completed:
Co-Actor Network:

Built a reusable Graph class to model undirected graphs.
Designed the TMDbAPIUtils class for interacting with the TMDb API.
Extracted and cleaned actor data from movies released in 1999 to generate a co-actor network.
SQLite Database:

Created and partitioned tables (movies, movie_cast, cast_bio) for efficient querying.
Answered analytical questions about top actors, high-scoring movies, and collaborative relationships.
Created and queried views to highlight collaborative actors and their scores.
Leveraged Full-Text Search (FTS) to analyze movie overviews for specific keywords.

**End Result Deliverables:**

Python files for implementing the Python and SQL tasks.
nodes.csv and edges.csv representing the co-actor graph.
Answers to specific questions using SQL queries.
Key Outcomes:

A graph-based visualization of actor relationships in movies.
Insights into high-performing actors, movies, and collaborations from the SQLite database.
This project demonstrates the practical application of APIs and databases to model and analyze real-world datasets efficiently.
