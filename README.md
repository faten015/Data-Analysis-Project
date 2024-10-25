In this project, three tasks were analyzed:

Task 1 Naive Bayes Classifier:

In this task, I explored and analyzed a dataset related to lung cancer diagnosis using machine learning techniques, specifically applying the Naive Bayes algorithm to predict lung cancer occurrence based on various health indicators like smoking habits and age. The dataset comprised 3,000 entries with 16 features, including both demographic and health-related factors, where the primary target variable indicated the presence of lung cancer ('Yes' or 'No').

I performed data preprocessing by encoding categorical features and splitting the dataset into training (80%) and testing (20%) sets. The Naive Bayes classifier was implemented, yielding moderate performance metrics: an accuracy of 52.83%, precision of 52.28%, recall of 57.72%, and an F1 score of 54.86%, indicating a better ability to identify lung cancer cases compared to overall predictions.

Through visual analyses, I examined the factors influencing lung cancer diagnosis, revealing that older age groups and smokers showed a higher likelihood of developing lung cancer, along with significant associations with symptoms such as cough and other health conditions.

Task 2 : Market Basket Analysis
I conducted a market basket analysis using a dataset containing transaction records, focusing on discovering patterns and associations between frequently purchased items. I preprocessed the data by loading it with Pandas, handling missing values, and converting it to a binary matrix for analysis. I then used the Apriori algorithm to identify groups of frequent items with a minimum of 1% support and created association rules to evaluate relationships between items based on support, confidence, and lift metrics. I performed visual analyses, creating bar charts of the top 10 best-selling products, histograms to show quantity distribution, and sales distribution by country to highlight regional differences in purchasing behavior.

Task 3 Text analysis 

I built a text classification model to categorize news data as "real" or "fake" using logistic regression, random forest, and Naive Bayes classifiers. The project involved preprocessing the text data by handling missing values and transforming the text into numerical vectors using TF-IDF vectorization. I trained the models on the processed data and performed hyperparameter tuning using GridSearchCV to improve performance. Finally, the predictions were saved and visualized through label distributions, cross-validation accuracy, and top TF-IDF features.
