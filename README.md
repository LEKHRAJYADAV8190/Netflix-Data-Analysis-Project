

# Netflix Data Analysis Project

## Project Overview

This project analyzes a dataset related to Netflix content, providing insights into various trends such as genres, release years, and more. The analysis is performed using Python and includes data cleaning, visualization, and export of the cleaned dataset.

## Features

- **Data Cleaning**: Handles missing values and ensures the dataset is ready for analysis.
- **Data Visualization**: Generates insightful visualizations, including bar charts and word clouds.
- **Export Functionality**: Saves the cleaned dataset for future use.

## Dataset

The dataset contains information about Netflix content, including:

- **Show ID**: Unique identifier for each show.
- **Type**: Movie or TV Show.
- **Title**: Name of the show.
- **Director**: Director(s) of the show.
- **Cast**: Cast members.
- **Country**: Country of origin.
- **Date Added**: Date when the show was added to Netflix.
- **Release Year**: Year the content was released.
- **Rating**: Content rating (e.g., PG, R).
- **Duration**: Duration of movies or the number of seasons for TV shows.
- **Listed In**: Genres/categories.
- **Description**: Brief summary of the content.

## Project Steps

1. **Data Loading**

   - The dataset is loaded into a Pandas DataFrame.

2. **Data Cleaning**

   - Checked for missing values and handled them appropriately.
   - Added a new column, `duration_numeric`, to convert durations into a numerical format for easier analysis.

3. **Visualization**

   - Generated bar charts to analyze content distribution by genre and release year.
   - Created a word cloud to visualize the most common words in content descriptions.

4. **Data Export**

   - Saved the cleaned dataset to a CSV file (`netflix_clean.csv`).

## Dependencies

- Python 3.11.5
- Pandas
- Matplotlib
- Seaborn
- WordCloud

## How to Run

1. Clone this repository or download the notebook.
2. Install the required dependencies using pip:
   ```bash
   pip install pandas matplotlib seaborn wordcloud
   ```
3. Open the Jupyter notebook file (`netflix_analysis.ipynb`) in Jupyter Notebook or any compatible environment.
4. Run the cells sequentially to perform the analysis.

## Output

- The cleaned dataset is saved as `netflix_clean.csv`.
- Visualizations are displayed inline within the notebook.

## Author

This project was created to analyze Netflix data and provide insights into its content library. Feel free to contribute or suggest improvements!


