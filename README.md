## Movies ETL
Using ETL on three different data sets to analyze movies, their details and user ratings

### Resources
- Data Sources: ratings.csv (file with user movie ratings too large to upload), movies_metadata.csv, wikipedia-movies.json
- Software: PostgreSQL 11, pgAdmin 4, Visual Studio Code, Jupyter Notebook 6.3.0, Pandas library, Matplotlib library

### Project Overview
- Read in the csv data files and the json file 
- Converted json file and csv files to DataFrames to clean data 
- Changed data types, eliminated superfluous columns and not usable rows, used regex to detect and change patterns, merged columns, renamed columns
- Merged the cleaned DataFrames
- Loaded the final DataFrames into SQL databases
