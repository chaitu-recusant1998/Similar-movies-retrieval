# Similar-movies-retrieval

• Accomplished the development of a movie recommendation system by importing 3 raw CSV datasets on movies, ratings and tags into Pandas dataframes, merging over 180,000 rows using movieID, and migrating into a normalized SQL database architecture.

• Led the design and implementation of similarity algorithms in Python and SQL to take in a user-specified movie ID and return a list of recommended movies matching on either common genres or similar tags.

• Directed the complex ETL pipeline from raw CSV files into a SQL database, handling data cleaning issues like duplicate removal and the conversion of the pipe-separated genres column into a separate associative table to link movies and genres.

• Improved recommendation relevance and personalization by enhancing the initial genre-matching algorithm to also incorporate weighted tag similarity, retrieving movies tagged by other users with terms similar to the input movie.

• Evaluated overall system effectiveness through substantive testing by inputting sample movie IDs and validating that the outputs contained expected movie titles based on genre overlaps or tag similarities.

• Achieved a fully functional movie recommendation system leveraging Python, Pandas, SQL, and customizable similarity logic, ready for integration into a user-facing web or mobile platform to deliver personalized suggestions at scale.
