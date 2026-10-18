# Airbnb Exploratory Data Analysis (EDA)

## Project Overview
This project explores Airbnb listing data using Python to identify pricing trends, room type distributions, neighborhood differences, availability patterns, and host behavior.

## Objectives
- Clean and preprocess Airbnb data.
- Analyze room types and neighborhood groups.
- Explore price distributions and extreme values.
- Investigate relationships between price, availability, reviews, and beds.
- Present findings using data visualizations.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)

## Data Cleaning
- Handled missing values in `price`, `neighborhood`, and `beds`.
- Converted `last_review` to datetime format.
- Examined extreme prices and capped values above $1,000 for selected visualizations.

## Exploratory Data Analysis

### 1. Room Type Distribution
Used bar charts to compare room types. Entire homes/apartments were the most common room type in the analyzed dataset.

### 2. Neighborhood Group Analysis
Compared prices across neighborhood groups. Manhattan had the highest average prices, followed by Brooklyn.

### 3. Price Distribution
Used histograms and boxplots to examine prices, identify outliers, and understand the distribution. Most listings were priced between $50 and $300 in the analyzed data.

### 4. Availability and Reviews
Used heatmaps and pair plots to explore relationships among price, availability, number of reviews, and beds.

### 5. Host Analysis
Used boxplots and listing comparisons to investigate hosts managing multiple listings and identify patterns associated with professional hosting.

## Visualizations
- Bar charts for room types and neighborhood groups
- Histograms for price distributions
- Boxplots for outlier analysis
- Heatmaps for numerical correlations
- Pair plots for relationships between selected variables

## Key Findings
1. Manhattan had the highest average listing prices, followed by Brooklyn.
2. Entire homes/apartments were more common and generally more expensive than private or shared rooms.
3. Extreme price values highlighted the importance of outlier investigation.
4. Availability and review activity showed patterns worth further investigation; correlation does not establish causation.
5. Some hosts managed multiple listings, suggesting the presence of professional hosting operations.

## How to Run
1. Clone or download this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the notebook in VS Code or Jupyter Notebook.
4. Ensure the dataset path is correct.
5. Run the notebook cells sequentially.

## Skills Demonstrated
Data cleaning, exploratory data analysis, data visualization, outlier investigation, correlation analysis, and Python-based data analysis.

## Author
Shivali Jain
