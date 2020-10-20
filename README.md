# Sentiment-Analysis-of-product-listed-on-Amazon
5000 customer reviews are scrapped by using scrapy
The product has more than 76% of positive reviews from its customers
The sentimental analysis on the customer reviews is matching with the customer ratings
The polarity chart clearly shows negative skewness as it has more positive reviews
Scatter plot for polarity scores and subjectivity scores shows a positive correlation 
Topic modelling by LDA is considered for the further analysis as it is giving more specific clustering of the words compared to NMF for this case
From the topic distribution plot, it is evident that most of the customer reviews are about the performance and the quality of the product
And we also see a topic related to customer disappointment about the product warranty, durability of the product and genuineness of the product description in the website
From both the topic modelling and from the sentiment analysis for the customer reviews it is concluded that the customer are happy and satisfied with the product
Random forest, SVM, Logistic regression, XGBOOST and Naive bayes classification models are built for the review data 
As the data shown more imbalance in its classes SMOTE has been applied for all the models
SVM model with SMOTE application shows the better metrics for all the three classes
Automation of reviews extraction is done by scheduling it in windows task scheduler on weekly basis 
Model has been deployed using Streamlit to get the sentiment of new review
Model deployment is also done for getting sentiment analysis for the current week reviews
