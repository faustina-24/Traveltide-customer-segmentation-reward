# Traveltide-customer-segmentation-reward
Executive Report

Traveler Segmentation and Analysis Project

Project Overview
This project aimed to segment travelers based on their behavior and characteristics to enhance customer satisfaction through personalized perks. The project involved selecting relevant customer data, performing exploratory data analysis (EDA), clustering using k-means, scaling, and establishing thresholds to categorize travelers into specific segments. The final output was a CSV file containing traveler types, user counts, and associated perks, which was visualized and analyzed using Tableau.

Data Selection and Preparation

Data Selection
Criteria: Customers were selected from the database with session dates starting from 2023-01-04 and having more than 7 sessions.

 Tools Used: Pandas library in Python.

Data Cleaning and Preprocessing
Data Cleaning: Handled missing values, corrected data types, and ensured data consistency.
 Scaling:  Normalized the data to ensure fair clustering using techniques like StandardScaler.

Exploratory Data Analysis (EDA)

Analysis Goals: Understand the distribution of key variables, identify patterns, and detect outliers.
Techniques: Utilized descriptive statistics, histograms, box plots, and correlation matrices.
Insights: Identified significant features influencing traveler behavior, such as age, number of trips, total nights, and presence of children.

Clustering and Segmentation

 K-Means Clustering:
 Purpose: Group travelers into distinct segments based on their characteristics.
 Process
 Determined the optimal number of clusters using the elbow method.
 Applied k-means clustering to categorize travelers into groups.
 Clusters Identified: Normal, Family, Business, Senior, and Solo travelers.




Defining Segments:
 Normal Traveler: Average travel behavior, not fitting other specific categories.
 Family Traveler: Travels with children, often on vacations.
 Business Traveler: Frequent travel for work purposes.
 Senior Traveler: Older customers , travel primarily for leisure.
 Solo Traveler: Young adults, traveling alone.


Exporting Data and Perk Assignment

Perk Assignment: Assigned specific perks to each traveler type to enhance their travel experience.
CSV Export: Compiled the traveler types, count of users, and their respective perks into a CSV file.


Visualization and Analysis

Tableau Visualization:
Purpose: Visualize the segmentation results and analyze the distribution of traveler types.
Charts Used: Bar charts, pie charts, and heat maps.
Insights: Identified the most prevalent traveler types and the effectiveness of assigned perks.

Presentation Preparation:
Slides Content:
Project overview and objectives.
Data selection and preprocessing steps.
EDA findings and insights.
Clustering process and results.
 Perk assignment and rationale.
 Visualization of traveler segments and their distribution.
 Tools Used: PowerPoint and Tableau for creating and embedding visualizations.

Key Findings

Traveler Distribution:
Normal Travelers: Largest group (2032).
Family Travelers: Significant segment (1958).
Business Travelers: Substantial segment (1382).
Solo Travelers: Smaller yet notable group (458).
Senior Travelers: Smallest segment (168).





Perk Effectiveness:
Free hotel meals for Normal Travelers.
Free checked bags for Family Travelers.
No cancellation fees for Business Travelers.
 1-night free hotel stay for Solo Travelers.
 Exclusive discounts for Senior Travelers.

Future Recommendations

Validation and Testing:
 Conduct A/B tests to compare traveler engagement and satisfaction with different perks.
 Use chi-squared tests to analyze the significance of perk preference across segments.


Data Collection and Supervised Learning:
Gather more detailed data on traveler preferences through surveys and feedback mechanisms.
 Train machine learning models to refine and enhance traveler segmentation.


Continuous Improvement
Regularly update the segmentation criteria and perks based on new data and evolving traveler behaviors.
Use insights from machine learning models to personalize offers and improve customer experience.


Conclusion
This project successfully segmented travelers into distinct categories and assigned targeted perks to enhance their travel experience. The analysis was visualized using Tableau, providing valuable insights into traveler distribution and perk effectiveness. Moving forward, further validation, testing, and data collection will help refine these segments and ensure the perks offered continue to meet traveler needs effectively.


Traveltide customer segmentation analysis 

https://colab.research.google.com/drive/1ZqpGovJZcAR8SPlTQSGGD3P9qlRNCPzJ?usp=sharing
