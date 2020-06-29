## End to End Database solution of US Wildfires Database
This project demonstrated end to end Database Solution in MySQL for storing and using ~1.88 million records of wildfires in The USA.

## Data Source/ Meta Data Link
https://www.kaggle.com/rtatman/188-million-us-wildfires

## Highlights of Processes Followed
- Data Normalization Process - Data Tables were designed and normalization processes were followed to bring the data tables to third normal form
- Data Modelling Process - Data Models using ER Diagrams were designed to define the structure of the data tables in 3rd normal form in the database
- Forward Engineering Process - Using forward Engineering process, the data tables were physically created in the database based on the data models (ER Diagram)
- Building Data Pipelines - Since data was in sqlite format which we cannot import directly onto MySQL, data pipeline was created to connect R-Studios to MySQL
- Data Manupulation and Loading - The sqlite datafiles were read using R-Studios, data fields and special characters were reformated to comply to utf8mb4 format
- Data Verification - SQL Queires were used to verify the correctness of data in the respective tables
