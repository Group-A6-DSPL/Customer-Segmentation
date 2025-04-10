# Customer-Segmentation

## Project Overview
KJ Marketing, a leading retail supermarket chain in Sri Lanka, aims to enhance its marketing strategies by adopting a personalized approach. Traditional marketing methods have failed to engage its evolving customer base, prompting the need for a data-driven segmentation strategy. This project focuses on classifying new customers into six predefined segments based on their purchasing behavior across three key product categories:
- **Dry Goods**: Non-perishable items like cereals, snacks, and beverages.
- **Fresh Produce**: Perishable goods such as fruits, vegetables, and dairy products.
- **Luxury Items**: High-end products such as fashion, electronics, and gourmet foods.

## Objective
The objective of this project is to develop a clustering model that accurately classifies new customers into predefined customer segments based on their historical purchasing patterns. The insights gained from this segmentation will allow KJ Marketing to optimize personalized marketing campaigns and improve customer engagement.

## Customer Segments
The following six customer segments have been identified based on historical sales data:

| Cluster Number | Cluster Name                | Outlet City | Fresh Sales | Dry Sales | Luxury Sales |
|---------------|----------------------------|------------|------------|-----------|--------------|
| 1             | Essential Budget Buyers     | Both       | Very Low   | High      | Very Low     |
| 2             | Premium Urban Spenders     | Mostly Urban | Very High | Very High | Highest      |
| 3             | Discount Shoppers          | Both       | High       | Very Low  | Lowest       |
| 4             | Minimalist Buyers          | Mostly Urban | Lowest    | Low       | Low          |
| 5             | Bulk & Premium Buyers      | Mostly Urban | Low       | Highest   | Very High    |
| 6             | Luxury & Fresh Buyers      | Both       | Highest    | Lowest    | High         |

### Segment Descriptions:
- **Essential Budget Buyers**: Price-sensitive customers who focus on staple products, spending high on dry goods but very low on fresh and luxury items.
- **Premium Urban Spenders**: High-income shoppers preferring premium-quality products, with very high fresh and dry sales and the highest luxury sales. Mostly urban.
- **Discount Shoppers**: Value-driven customers with high fresh sales but very low dry and the lowest luxury sales, balancing between urban and suburban areas.
- **Minimalist Buyers**: Customers with the lowest fresh sales and low dry and luxury sales, primarily in urban areas.
- **Bulk & Premium Buyers**: Large-volume buyers, including business owners and large households, with the highest dry and very high luxury sales.
- **Luxury & Fresh Buyers**: Health-conscious and brand-loyal customers focused on fresh and high-end products, with the highest fresh and high luxury sales but the lowest dry sales.

## Methodology
1. **Data Collection & Preprocessing**
   - Cleaning and transforming historical sales data.
   - Handling missing values and standardizing features.
2. **Feature Engineering & Selection**
   - Selecting relevant features.
   - Scaling numerical data for optimal clustering performance.
3. **Model Evaluation & Validation**
   - Testing different clustering algorithms to identify the most accurate segmentation.
   - Cross-validating results and refining clusters.
4. **Deployment & Application**
   - Developing a classification model to predict customer segments for new customers.
   - Integrating insights into KJ Marketing’s personalized marketing strategy.

## Technologies Used
- **Python** (pandas, numpy, scikit-learn, seaborn, matplotlib)
- **Machine Learning** (K-Means, XGBoost, LightGBM, RandomForest, Multinomial Logistic Regression for classification)
- **Data Visualization** (Seaborn, Matplotlib, Plotly)
- **Jupyter Notebook**

## Contributors
-  Hikma Shazneen 
-  Aaliyah Shakoor 
-  Hansa Wijeratne 
-  Livin John 
-  Muhammed Saneej 
