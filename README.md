# Zomato Dataset: Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Zomato dataset to gain insights into various aspects of restaurants such as ratings, locations, and popular cuisines. This beginner-friendly project introduces key data analysis techniques that help prepare the dataset for predictive modeling or decision-making purposes.

## Project Overview

The Zomato dataset provides detailed information about restaurants, including their location, cuisines offered, and customer ratings. The objectives of this project are:
- **Data Exploration**: Discover patterns and trends in the dataset.
- **Data Visualization**: Use visualizations to represent key insights such as restaurant ratings, popular cuisines, and city-wise distribution.
- **Insight Generation**: Extract valuable insights that can guide business strategies and improve decision-making.

## Key Steps in the Project

### 1. Data Preprocessing
- Cleaned the dataset by handling missing and irrelevant data.
- Extracted the most relevant columns like `Restaurant Name`, `City`, `Cuisines`, and `Rating`.
- Ensured consistent formatting for categorical and numerical data.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of restaurants by city and their corresponding ratings using **bar charts**, **pie charts**, and **histograms**.
- Analyzed popular cuisines in each city and identified trends in customer preferences.
- Investigated which cities host the highest number of top-rated restaurants, providing insights into regional preferences.

### 3. Feature Extraction
- Extracted key features such as `Cuisine` and `City` to identify which attributes correlate with higher restaurant ratings.
- Used **heatmaps**, **correlation matrices**, and other visual tools to uncover relationships between features.

## Insights & Findings
- **City-Wise Restaurant Distribution**: Certain cities have significantly more restaurants, reflecting different market sizes.
- **Cuisine Popularity**: Some cuisines are more commonly found in high-rated restaurants, indicating possible customer preferences.
- **Top-Rated Locations**: Cities like `Delhi`, `Bangalore`, and `Mumbai` house the majority of highly-rated restaurants, revealing potential hotspots for quality dining.

## Next Steps
This EDA forms the foundation for more advanced analyses, including:
- **Predictive Modeling**: Develop models to predict restaurant success based on location, cuisine, and other factors.
- **Recommendation Systems**: Create personalized restaurant recommendations based on user preferences and past ratings.

## Tools & Libraries Used
- `pandas`: For data manipulation and preprocessing.
- `numpy`: For efficient numerical operations.
- `matplotlib`: For creating basic visualizations such as bar and pie charts.
- `seaborn`: For enhanced data visualization, including correlation matrices and advanced plots.




## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Aishjahan/Zomato-Dataset-EDA-and-Feature-Engineering
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook to view the EDA.
