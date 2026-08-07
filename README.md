# Yelp-Restaurant-Analysis — Customer Engagement vs Rating

## Project Overview

This project analyzes the Yelp dataset to understand whether customer engagement is a strong indicator of restaurant ratings.

The analysis focuses specifically on restaurants and examines whether metrics such as:

- Restaurant Ratings
- Number of Reviews
- Number of Tips
- Number of Check-ins

are related to each other.

## Business Question

Is customer engagement a strong indicator of restaurant rating?

Customer engagement can indicate how actively customers interact with a restaurant. In this project, engagement is measured using:

- Reviews — Number of customer reviews
- Tips — Number of tips/comments left by customers
- Check-ins — Number of customer check-ins

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

## Project Workflow

- Yelp JSON Dataset
- Load Data in Chunks
- Filter Restaurant Businesses 
- Store Data in SQLite 
- SQL Analysis 
- Aggregate Reviews, Tips & Check-ins 
- Analyze Relationship with Ratings
- Visualization

## Conclusion

The analysis shows that customer engagement generally increases as restaurant ratings increase, up to around 4 stars. However, engagement decreases for restaurants rated above 4 stars.

Although highly rated restaurants tend to have higher customer engagement, the correlation between engagement metrics and ratings was relatively weak. This suggests that customer engagement alone is not a strong predictor of restaurant ratings.

Other factors such as food quality, service, price, and customer experience may also play an important role in determining restaurant ratings.
