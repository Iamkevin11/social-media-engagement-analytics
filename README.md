# Social Media Engagement Analytics Using Python

## Project Overview

This project analyzes **5,000 social media records** to explore audience engagement patterns and identify factors associated with social media post performance.

The analysis examines engagement across post types, content categories, countries, age groups, account verification status, sentiment, and device types. Python libraries were used for data cleaning, exploratory data analysis, statistical analysis, feature engineering, and visualization.

## Objectives

- Clean and prepare the dataset for analysis.
- Explore audience engagement patterns using Pandas and NumPy.
- Calculate descriptive statistics and examine relationships between numerical variables.
- Engineer features such as engagement score, hashtag count, and log-transformed metrics.
- Visualize patterns using Matplotlib, Seaborn, and Plotly.
- Identify high-performing content categories and differences across countries, age groups, and devices.

## Tools and Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas** — data cleaning and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Plotly** — interactive charts

## Project Workflow

1. **Data Loading and Inspection:** Imported the CSV dataset and examined its structure, columns, and data types.
2. **Data Cleaning:** Checked missing values and duplicates, standardized selected categorical values, and handled unrealistic metric values.
3. **Exploratory Data Analysis:** Examined numerical summaries, categorical distributions, correlations, and grouped metrics.
4. **Feature Engineering:** Created an engagement score, hashtag count, and log-transformed metrics.
5. **Statistical Analysis:** Calculated mean, median, mode, standard deviation, variance, and percentiles.
6. **Data Visualization:** Created charts using Matplotlib, Seaborn, and Plotly.
7. **Insights and Recommendations:** Compared engagement across content types, categories, countries, age groups, verification status, sentiment, and devices.

## Key Findings

- **Post type:** Video posts had the highest average engagement rate (1.12), while reels had the lowest (0.78).
- **Content category:** Food had the highest average engagement rate (1.36), followed by technology (1.16).
- **Country:** Brazil recorded the highest average engagement rate (1.54), followed by Australia (1.32).
- **Age group:** The 46–60 age group had the highest average engagement rate (1.15) among the analyzed age groups.
- **Account verification:** Verified accounts had a higher average engagement rate (1.05) than non-verified accounts (0.95), although their average likes were lower.
- **Device type:** Mobile users had the highest average watch time and engagement rate among the analyzed devices.
- **Sentiment:** Posts labeled negative had the highest average engagement rate (1.04). Higher engagement does not necessarily mean more positive audience feedback.
- **Posting time:** A reliable best posting hour could not be identified because all records were assigned hour 0 in the analysis.

*These are descriptive findings from this dataset and do not establish causal relationships.*

## Visualizations

The project includes static and interactive visualizations, including:

- Likes versus impressions scatter plot
- Daily trend line chart
- Post category and post type comparisons
- Gender distribution pie chart
- Age distribution histogram
- Engagement rate box plot
- Average likes by category
- Follower count by sentiment
- Correlation heatmap and pair plot
- Engagement by device type
- Interactive Plotly line, bar, bubble, and scatter charts

## Repository Contents

- `social_media_engagement_analytics.ipynb` — notebook containing the analysis and visualizations.
- `social_media_engagement_final.csv` — cleaned and analyzed dataset.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```

3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Ensure the required input CSV file is available at the path used in the notebook.
5. Run the notebook cells in order.

## Conclusion

This project demonstrates a complete Python-based data analytics workflow, from data preparation and exploratory analysis to statistical summaries, visualization, and insight generation. The findings can help guide further testing of content strategies and audience engagement patterns.

## Author

Created as part of a Data Analytics course project.
