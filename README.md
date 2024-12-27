# COGNIFYZ-TECHNOLOGY-DATA-SCIENCE-INTERNSHIP
Problem Statement  

Level 1: Data Exploration and Analysis  
Objective: To develop fundamental data science skills by exploring, cleaning, and analyzing a restaurant dataset.  
Tasks: Examine the dataset structure, handle missing values, convert data types as necessary, and analyze class imbalances. Calculate key statistical metrics, evaluate distributions of categorical variables, and identify leading cuisines and cities.  
Significance: Build a solid foundation in data exploration and descriptive analysis, essential for data-driven decisions in the restaurant industry.  

Level 2: Advanced Analysis  
Objective: Uncover deeper insights into restaurant services, pricing trends, and customer preferences through advanced analytical techniques.  
Tasks: Analyze the availability of table bookings and online delivery services, compare ratings for these services, and identify common price ranges. Determine average ratings by price range and correlate them with restaurant colors. Implement feature engineering to enrich dataset intelligence.  
Significance: Gain a detailed understanding of customer behavior, restaurant services, and pricing strategies.  

Level 3: Predictive Modeling and Insights 
Objective: Predict restaurant ratings, analyze customer preferences, and create visualizations to support decision-making.  
Tasks: Build regression models to forecast ratings and evaluate their performance. Investigate the relationship between cuisine types and ratings, identify popular cuisines, and analyze their rating patterns. Generate visualizations to represent rating distributions, average ratings, and feature correlations.  
Significance: Enable data-driven decision-making by predicting restaurant performance and identifying customer preferences effectively.  

---

 Project Summary 

#### Level 1: Data Exploration and Analysis 
1. Conducted a thorough exploration of the dataset, ensuring data completeness and integrity.  
2. Performed descriptive analysis to extract essential statistical metrics and identified popular cuisines and cities.  
3. Incorporated geospatial insights to analyze restaurant locations and their correlation with ratings.  

#### Level 2: Advanced Analysis  
1. Investigated table booking and online delivery services to understand their impact on customer preferences.  
2. Identified the most frequent price range and correlated it with higher ratings.  
3. Utilized feature engineering techniques to enrich data intelligence and uncover meaningful patterns.  

#### Level 3: Predictive Modeling and Insights  
1. Built predictive models, with Random Forest delivering superior accuracy in predicting aggregate ratings.  
2. Explored the influence of cuisine types on ratings, identifying popular cuisines with consistent performance.  
3. Designed visualizations to reveal distribution patterns, rating trends, and key feature correlations.  

---

### Key Insights 

#### 1. Data Overview and Exploration:  
- Dataset contained 9,551 records with 21 columns, showcasing minimal null values, primarily in the ‘Cuisines’ column.  
- No duplicates were present, and no significant data type conversions were required.  
- Aggregate ratings followed a balanced distribution.  

#### 2. Descriptive Statistics:  
- Identified key metrics for numerical columns.  
- Cities like New Delhi, Gurgaon, and Noida led in restaurant counts, with prominent country codes being 1 and 216.  
- North Indian and Chinese cuisines emerged as the most popular.  

#### 3. Geospatial Insights:  
- India and North America were dominant regions for restaurant presence.  
- New Delhi had the highest concentration of restaurants, followed by Gurgaon and Noida.  
- Latitude showed no correlation with ratings, while longitude exhibited a slight negative correlation.  

#### 4. Table Booking and Delivery Services:  
- Only 12.12% of restaurants offered table booking, while 25.66% provided online delivery services.  
- Restaurants with table booking had an average rating of 3.44, significantly higher than the 2.56 average for those without.  
- Online delivery was more common among medium-priced restaurants.  

#### 5. Price Range Analysis: 
- Price range 1 was most frequent, but price range 4 garnered the highest average ratings, followed by ranges 3, 2, and 1.  

#### 6. Feature Engineering:  
- Created columns to measure the length of restaurant names and addresses.  
- Added binary indicators for table booking and online delivery services using categorical encoding.  

#### 7. Predictive Modeling:  
- Implemented Linear Regression, Decision Tree, and Random Forest models to predict ratings.  
- Random Forest achieved the best performance with the lowest Mean Squared Error (MSE) and highest R-squared value.  

#### 8. Customer Preference Analysis: 
- Cuisines like Mughlai, North Indian, and Fast Food had the most significant impact on ratings.  
- Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines received the highest average ratings.  
- North Indian, Mughlai, and Chinese cuisines were the most popular by vote count.  

#### 9. Visual Insights:  
- Restaurant ratings exhibited a negatively skewed distribution.  
- Cities like Inner City, Quezon City, and Makati City had the highest average ratings.  
- A strong positive correlation between votes and ratings was identified.  

---
## Conclusion:  
This project provided a comprehensive exploration of restaurant data, enabling valuable insights into customer preferences, services, pricing, and rating predictions. It demonstrated the importance of data-driven approaches for understanding market trends and enhancing decision-making in the restaurant industry.
---

## Author
- [Adhiraj Karjee](https://www.linkedin.com/in/adhiraj-karjee-b993b0248/)
 ----
 ## Reference
 - [Cognifyz Technologies Data Science Internship](https://www.cognifyz.com/careers/career.html)
