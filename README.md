# Real Estate & Airbnb Market Analysis
This project explores how property prices and rental performance are shaped across two different markets: traditional residential housing and short-term rentals. The work combines exploratory analysis with machine learning to understand what actually drives value, how predictable these markets are, and where simple models break down.

**Quick Summary**

**Markets analyzed**: Austin housing and Airbnb listings

**Main tasks:** price prediction, classification, and market segmentation

**Best models**: ensemble methods, especially Gradient Boosting

**Data Used**

- Austin housing listings with property features like price, size, year built, home type, and school ratings

- Inside Airbnb listings with host behavior, reviews, availability, and pricing

- A national USA real estate dataset that was explored but excluded from final modeling due to weak predictive signal

**Because the datasets are large, raw data files are not included. All notebooks are designed to run locally in Jupyter.**

**What I Did**

- **Data preparation:**
Cleaned missing values, handled outliers, encoded categorical variables, scaled features when needed, and inspected class imbalance.
- **Exploratory analysis:**
Used distributions, boxplots, correlations, and PCA to understand how price relates to property features and host behavior. This step guided which models were worth using.
- **Modeling:**
Built baseline linear models, then tested regularized regression, KNN, decision trees, random forests, support vector machines, and gradient boosting. I also framed pricing as a classification problem to study high-performing listings.
- **Clustering:**
Applied K-Means, DBSCAN, and hierarchical clustering to see whether natural market segments existed, especially in Airbnb data.

**Results at a Glance**
- Gradient Boosting achieved the strongest regression performance on Airbnb pricing with R² around 0.72
- Random Forest models reached about 82 percent accuracy for identifying high-priced or high-performing listings
- Austin housing prices were driven mainly by size, bathrooms, and school quality
- Airbnb pricing depended more on reviews, host responsiveness, and availability
- Airbnb listings formed clear price tiers, while housing prices varied more continuously


## Technologies Used

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)  
- Jupyter Notebook (via Anaconda Navigator)  
- Machine Learning: Linear Regression, Random Forest, PCA, Clustering  
- Git & GitHub
---


## Datasets used:  
- [Inside Airbnb](https://insideairbnb.com/get-the-data/)
- [Austin Housing Prices](https://www.kaggle.com/datasets/ericpierce/austinhousingprices)
- [USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)

