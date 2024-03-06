# Magazine-Churn-Wizard


A big problem for magazine publishers is keeping their subscriber base and reducing cancellations. Publishers can proactively identify at-risk customers and adopt specific retention efforts by predicting whether customers would churn.

“Customer churn, also known as customer attrition, is the process by which customers stop doing business with a company. While some degree of customer churn is inevitable, keeping it to a minimum is essential. High customer churn rates can significantly impact revenue and growth and can even put a company out of business.” [1]

Hence, predicting customer churn has become a crucial task with the development of data-driven methodologies. Major sellers like Amazon have databases and review collections to make predictions, but independent publishers or sellers do not have such resources at their disposal. To make predictions for those, readily available Amazon magazine subscription reviews data have been used to try and build a better approach where inputting their customer feedback or reviews will predict if they are at risk of dropping the subscription. Magazine publishers can use this valuable tool for preventative churn management. Publishers can implement targeted retention methods, such as personalized offers, enhanced customer support, or content recommendations, by identifying consumers at high risk of canceling.

There are tools like VADER or Text Blob, which can help in finding the sentiment of the text that is inputted, but they are only sometimes accurate. In this project, a detailed comparison between sentiment analysis tools like Vader and classifier models has been made, and the results show that the trained classifier models perform better. Different approaches have been used in training the classifier to compare and choose which performs the best with a careful train test split. A random bad review comment has been picked up from the internet for the magazine
"Better Homes & Gardens,” and compared the results from Vader and the classifiers to check if they would predict whether the customer churns.

# References

1. Subscription Flow.com. (2022). Customer Churn Vs. Revenue Churn.
