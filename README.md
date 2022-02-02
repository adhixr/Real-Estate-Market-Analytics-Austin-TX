# Austin-House-Price-Analysis
Here is our analysis of the Austin Housing Dataset sourced from Zillow.com. We ran queries to build data visualizations and ML models for data analysis on DataBricks to understand the fluctuation in house prices based on the significant factors in the dataset.

BUSINESS -
Austin, TX had the highest percentage property price increase last year and is currently the hottest real estate market in the US. The Austin Board of Realtors recently reported a 26.3% increase in the area’s median home price from October 2019 to October 2020. 
The median price for a home in the Austin region is $365,000. A home located within the city of Austin sits at a median $441,250. 

The top 5 cities with the hottest real estate markets were -Austin, Phoenix,Nashville, Tampa and Denver (in that order).


TECHNICAL-
In the recent years, Machine Learning Algorithms are being widely used to predict house prices in the real estate market. ML models also offer interesting insights in analyzing various factors and how they contribute to house price fluctuations.
The purpose of this project was to dig deep and develop a good understanding of how to leverage ML models to study price fluctuations due to these factors as an interesting business use case.


Content:

1.Visualisations using SQL queries

2.Data Cleaning

3.Challenges Faced

4.Linear Regression

5.Linear SVC

6.Comparison of Logistic and Linear SVC based on their accuracies

7.Logistic Regression



The dataset for Austin, TX House Listings contains features and Images scraped in January 2021.

These home listings were scraped from Zillow.com using their official API, via apify.com. This data was scraped on January 31st, 2021.

Please see the .ipynb file for the code and the step-by-step results.

Business Takeaways-

Interpretration – From the final centroid values we infer that:

1.The house price is comparatively higher when the number of bedrooms and number of bathrooms are >3 even if the area in sq ft of the house is less.

From cluster 1 and 8, we can say that a house with 2 bathrooms and 3 bedrooms will cost around 400K if the living area is around 2000 sq.ft.

2.The centroid with the least price is the 1st one with 250K, it is most likely to have 2 bathrooms, 3 bedrooms and an average living area of 1618 sq.ft. and on similar terms, looking at cluster 4 (7.2 million has on average, 7 bathrooms, 5 bedrooms and a living area of around 7938 sq.ft which of course, makes sense of the clustering analysis.

3.Looking at median numbers of the cluster centroids (7th one at 850K, has, on average, 3 bathrooms, 4 bedrooms and a living area of around 3000 sq.ft.

Of course, there are many other aspects to be considered as per the variables in this dataset and this is just a view and understanding of one simple aspect of effect on house price for the three main variables of number of bathrooms, number of bedrooms and living area in sq.ft. Using the similar logic, we can carry out analysis on other variables to see their induvial/combined effect on house price with different permutations and combinations.


