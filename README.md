# Yelp-Restaurant-Analysis — Customer Engagement vs Rating


## Business Question

Does higher customer engagement correspond to higher restaurant ratings on Yelp?


## Project Overview

This project analyzes Yelp restaurant data to understand the relationship between
customer engagement and restaurant ratings.

The analysis examines three customer engagement metrics — reviews, tips, and
check-ins — and compares them with restaurant ratings. The goal is to determine
whether restaurants with higher levels of customer engagement tend to receive
higher ratings.


## Business Metrics

- **Restaurant Rating** : The average star rating given by customers to a restaurant on Yelp, ranging from 1 to 5 stars. 
- **Reviews** : The number of customer reviews received by a restaurant. Reviews represent customers who provided detailed feedback about their experience. 
- **Tips** : The number of tips left by customers for a restaurant. Tips are short comments or recommendations shared by customers on Yelp. 
- **Check-ins** : The number of customer check-in records associated with a restaurant, representing customer visits or interactions recorded through Yelp.

  
## Dataset

The project uses the Yelp Open Dataset, which contains information about businesses, reviews, users, tips, and check-ins.

For this analysis, the focus was primarily on restaurant businesses and the following data sources:

- business.json
- review.json
- tip.json
- checkin.json

The original JSON files were large, so the data was processed in chunks before analysis.


## Tools Used

Python | Pandas | SQL | SQLite | Matplotlib | Seaborn


## Analysis Approach

The analysis was performed in three stages:

1. **Engagement vs. Rating**  
   Calculated restaurant-level review, tip, and check-in counts with restaurant ratings and visualized using scatter plots.

2. **Engagement by Rating**  
   Calculated the average number of reviews, tips, and check-ins for each restaurant rating and visualized using bar plots.

3. **Correlation Analysis**  
   Measured the correlation between each engagement metric and restaurant rating using heatmap.


## Key Findings

- Restaurants rated around **4 stars** showed the highest average levels of reviews, tips, and check-ins.
- Customer engagement and restaurant rating showed a **weak positive correlation**.
- The correlation with rating was **0.17 for reviews, 0.14 for tips, and 0.11 for check-ins**.
- The engagement metrics themselves were strongly correlated with each other, suggesting that restaurants receiving more reviews also tend to receive more tips and check-ins.
   

## Conclusion

The analysis suggests that higher customer engagement generally corresponds to higher restaurant ratings up to around 4 stars. However, engagement drops among 5-star restaurants.

Despite this pattern, the correlation between customer engagement metrics and restaurant ratings was relatively weak. Therefore, customer engagement alone does not appear to be a strong indicator of restaurant ratings.

Other factors such as food quality, service, price, and overall customer experience may also play an important role in determining restaurant ratings.

**Note:** The analysis identifies associations between customer engagement and ratings but does not establish that higher engagement causes higher ratings.
