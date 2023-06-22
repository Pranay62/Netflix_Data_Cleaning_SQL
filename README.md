## Netflix Data Cleaning and Visualization Project

Welcome to the Netflix dataset for data cleaning and visualization project. This project focuses on a cleaned version of the original Netflix dataset. The dataset includes movies, TV shows, and original content added to Netflix from 2008 to 2021, spanning from the oldest content in 1925 to the latest in 2021. The main objective of this project is to showcase data cleaning and visualization skills using PostgreSQL and Tableau, respectively.

## Dataset Details

The dataset used in this project is a cleaned version of the original Netflix dataset. The cleaned dataset can be accessed [here](link-to-cleaned-dataset). It includes the following columns:

- Title: The title of the movie, TV show, or original content.
- Release Year: The year when the content was released.
- Type: Indicates whether it is a movie or TV show.
- Director: The director(s) of the content.
- Cast: The cast members of the content.
- Country: The country where the content was produced.
- Duration: The duration of the content.
- Listed in: The genres or categories the content belongs to.
- Description: A brief description of the content.

## Project Steps

In this project, the following steps were performed on the Netflix dataset:

1. **Handling Null Values**: Null values in the dataset were identified and appropriate actions were taken to handle them effectively.
2. **Removing Duplicates**: Duplicate entries in the dataset were identified and removed to ensure data integrity.
3. **Populating Missing Rows**: Missing rows, if any, were populated using relevant information from the dataset.
4. **Discarding Irrelevant Columns**: Columns that were not relevant for the analysis or visualization were removed from the dataset.
5. **Splitting Columns**: Columns containing multiple values were split into separate columns to enable better analysis and visualization.

Please refer to the code comments and the provided SQL script for detailed information on the data cleaning steps.

## Visualization

The cleaned dataset was imported into Tableau for visualization purposes. A Tableau dashboard was created to showcase the insights and trends in the Netflix dataset. You can access the Tableau dashboard [here](link-to-tableau-dashboard).

## Usage

To replicate the data cleaning and visualization process:

1. Make sure you have a compatible database management system (DBMS) installed, such as PostgreSQL.
2. Download the Netflix dataset from the provided link and import it into your DBMS.
3. Copy the SQL code from the NetflixDatasets.sql file and execute it in your DBMS to perform the data cleaning steps.
4. Access the cleaned dataset and import it into Tableau for visualization.
5. Customize the Tableau dashboard as per your requirements.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use the provided code and dataset for your own purposes.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or additional insights related to the Netflix dataset, data cleaning, or visualization, please open an issue or submit a pull request.
