# Netflix Content Analysis

This project provides an in-depth analysis of the Netflix dataset. The entire process of data cleaning, preprocessing, exploratory data analysis, and visualization is contained within the `Project2.ipynb` Jupyter Notebook.

## Project Notebook

The core of this project is the `Project2.ipynb` notebook. It performs a comprehensive analysis of Netflix titles.

### Notebook Details

The notebook is structured into several key steps:

*   **Data Loading and Initial Inspection:** The `netflix1.csv` dataset is loaded into a pandas DataFrame, and an initial assessment of its structure and content is performed.

*   **Data Cleaning:**
    *   Duplicate entries are identified and removed.
    *   Missing values are handled, particularly for the `director` and `country` columns, to ensure data quality.

*   **Data Preprocessing & Feature Engineering:**
    *   The `date_added` column is converted to a proper datetime format.
    *   New features like `year_added` and `month_added` are extracted to facilitate time-based analysis.

*   **Exploratory Data Analysis (EDA) and Visualization:** A series of visualizations are created to uncover insights from the data:
    *   **Content Type Distribution:** A pie chart illustrating the breakdown of Movies vs. TV Shows.
    *   **Rating Distribution:** A bar chart showing the frequency of different content ratings (e.g., TV-MA, PG-13).
    *   **Top Content Producers:** Visualizations of the top 10 countries and directors contributing content.
    *   **Release Trends:** Line charts analyzing the growth of content added annually and the patterns of monthly releases.
    *   **Popular Genres:** A bar chart highlighting the top 10 most common movie genres.

