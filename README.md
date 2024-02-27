# Project "Is A “Centre-Forward” Footballer’s Market Value Determined only by Their Statistics?" By Gajan Kanagenthiran
- The "centre-forward-data-project-pyhton-code.ipynb" in the repository is a jupyter notebook file that contains the code for the Data Cleaning that was done such as Standardizing Data Types and Combining Multiple Datasets, while also including the code for the analysis technique and machine learning used on the data set for the  "Is A “Centre-Forward” Footballer’s Market Value Determined Only by Their Statistics?" project.

- The "FOOTBALL REPORT.pdf" is a pdf file in the repository that has an in-depth analysis of the dataset, results, methodology and findings. 

##### Problem Area: 
In professional football, there is an ongoing debate about how a player's market value is determined, especially for 'Centre-Forwards.' This study analyses the influence of goals and assists on the market value of the top 50 'Centre-Forwards' using the 'Most Expensive Footballers 2021' dataset.


##### Methodology: 
This project shows a range of data analyst skills and data-driven techniques while using essential Python libraries. 

•	Data Collection: The 'Most Expensive Footballers 2021' dataset was sourced from Kaggle.

•	Data Processing: Python was the primary language, utilising pandas for data manipulation and NumPy for numerical operations. Data cleaning ensured integrity, including creating the "Goals + Assists per match" metric.

•	Data Analysis/Machine learning Techniques: K-means clustering, and Linear Regression were employed to model the relationship between market value and performance statistics. The dataset was split into training and test data for linear regression.

•	Data Visualisation: Matplotlib was used for creating informative visualisations.

##### Results:
![Slide2](https://github.com/GK2103/GK2103.github.io/assets/99646891/8195b0e1-1619-4a43-bf13-dc8757552d5c)
![Slide3](https://github.com/GK2103/GK2103.github.io/assets/99646891/8e1f14be-2b32-4353-ac6a-db3fadd89982)

##### Findings: (Full analysis can be found in the project report PDF) 
The project's findings revealed that player performance statistics significantly affected the market values of footballers who were valued below £60 million, while higher-valued players above £130 million were influenced by a broader range of factors beyond statistics, such as age, league, and playing style. K-Means clustering provided additional insights by demonstrating that players with higher performance statistics tend to be valued more in the lower price range. The linear regression analysis indicated a small positive correlation (R-Value of 0.243) (Table 3) between market value and player performance statistics, although the model's fit was poor, as seen in Graph 2, suggesting a more complex relationship. In summary, while player statistics play a role in determining market values, their impact varies depending on a player's value range, highlighting the complex nature of football player valuation.
