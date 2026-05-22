# Key Findings:
Most Global Financial Giants' headquarters are situated in China and the United States which hints at the context that these two countries have a developed economy.</br>

The Conglomerate industry earns the most revenue on average, while the Insurance industry earned the most total revenue in 2024.</br>

The company's total assets isn't the main cause for large revenue but it is one of the components since it has a moderate influence on revenue and total revenue.
<br></br>

# Author/s: Imaan Adams
<br></br>

# Table of Contents
- [Business Problem](#Business-Problem)
- [Data Source](#Data-Source)
- [Methods](#Methods)
- [Tech Stack](#Tech-Stack)
- [Quick glance at the results](#Quick-glance-at-the-results)
- [Lessons learned and recommendation](#Lessons-learned-and-recommendation])
- [Limitations and what can be improved](#Limitations-and-what-can-be-improved)
</br>

# Business Problem

Questions to answer using data:
- Which industries had the most revenue on average/in total in 2024?
    - Group by industry, calculate average & total revenue
    - Visualization: Double bargraph 
- Does the company's total assets influence its revenue/income?
    - Calculate correlation between revenue, net income and total assets
    - Visualization: Correlation heatmap / Scatter plot
- Which countries do most of these companies have their headquarters in? (total companies belonging to a country)
    - Group by headquarters, total up companies in those groups
    - Visualization: Pie chart
</br>

# Data Source
Free Dataset from Kaggle, published by Prajwal Dongre.

https://www.kaggle.com/datasets/prajwaldongre/global-financial-giants-by-revenue-2024
</br>

# Methods
## Data Cleaning Pipeline
- Remove duplicates
- Standardize the data
- Edit Asset column name
- Deal with null or blank values

## Statistical Methods
- Correlation
- Descriptive Statistics (count, mean, median, mode, std, min, max & percentiles)

<br></br>

# Tech Stack
Pandas, Plotly, Scikit-learn, Numpy, Matplotlib
<br></br>

# Quick glance at the results
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/1d99b314-44b6-4c25-81ea-cdd1a7a77a4b" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/459959ea-81de-4dee-84ae-7efa8f9e22ac" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/72647a99-30ca-4005-b18e-f724852b3675" />
<img width="700" height="360" alt="Image" src="https://github.com/user-attachments/assets/bcedb5ea-64e7-42c6-be53-4ef136419b56" />
<br></br>

# Lessons learned and recommendation
I learned how to better filter exactly which data was needed to analyse, specifically, industries.</br>

Recommendations: 
If an entrepeneur wanted to start their business, they can use this data to find out which industry is most profitable.
<br></br>

# Limitations and what can be improved


Some improvements:

<br></br>
