# AI Project: Exploratory Data Analysis on a Car Dataset

## Project Objective

The goal of this project is to perform a comprehensive Exploratory Data Analysis (EDA) on a provided car dataset. The analysis focuses on identifying key patterns, relationships, and insights from the data. The primary tasks include data cleaning, data exploration, and creating insightful visualizations.

## Files in this Project

*   `cleaned_car_dataset.csv`: The raw dataset after undergoing a thorough cleaning and preprocessing pipeline. The original `has_warranty` column was dropped due to a high number of missing and inconsistent values.
*   `EDA_Car_Dataset.ipynb`: A Jupyter Notebook containing the full Python code, detailed analysis, visualizations, and conclusions. Its contents are provided below in a text-friendly format.
*   `visualizations/`: A directory containing all the charts and plots generated during the analysis. A list of these visualizations is provided at the end.

## Key Steps in the Analysis

1.  **Data Cleaning:**
    *   Handling duplicate entries.
    *   Correcting data types for all columns.
    *   Identifying and resolving inconsistencies and errors in columns like `price`, `mileage_kmpl`, and `brand`.
    *   Handling missing or invalid values (e.g., 'Unknown').
    *   Dropping the `has_warranty` column due to its poor data quality, which would not contribute meaningfully to the analysis.

2.  **Data Exploration & Visualization:**
    *   **Univariate Analysis:** Analyzing the distribution of individual features like `price`, `make_year`, `fuel_type`, and `brand` using histograms, count plots, and box plots.
    *   **Bivariate Analysis:** Exploring relationships between pairs of variables, such as `price` vs. `make_year`, `price` vs. `kilometer_run`, and the influence of categorical variables like `brand` and `fuel_type` on `price`.
    *   **Correlation Analysis:** A heatmap was used to visualize the correlation between numerical features.

3.  **Insights and Conclusion:**
    *   Summarizing the key findings from the analysis.
    *   Suggesting potential use cases for the data, such as building a price prediction model or a market analysis tool for dealerships.

## How to Run

1.  Ensure you have Python and Jupyter Notebook installed.
2.  Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Save the provided CSV data into a file named `cleaned_car_dataset.csv` in the same directory where you will run the notebook.
4.  Copy the code from the `EDA_Car_Dataset.ipynb` section below into a new Jupyter Notebook and run it. The `visualizations` directory will be created automatically, and all plots will be saved there.
