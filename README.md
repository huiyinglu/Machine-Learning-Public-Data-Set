# Machine-Learning-Public-Data-Set
Machine Learning projects - using public dataset

This repository includes the following projects:
1. finding_donors.ipynb:
   In this project, we employ several supervised algorithms (Random Forest, AdaBoost, and GradientBoosting) to accurately model
   individuals' income using data collected from the 1994 U.S. Census. We will then choose the best candidate algorithm (GradientBoosting)
   from preliminary results and further optimize this algorithm (use grid search) to best model the data. The final accuracy score is
   pretty impressive! The goal with this implementation is to construct a model that accurately predicts whether an individual makes more
   than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an
   individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out
   to begin with.

   The dataset for this project originates from the UCI Machine Learning Repository. The datset was donated by Ron Kohavi and Barry Becker,
   after being published in the article "Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid". You can find the 
   article  by Ron Kohavi online. The data we investigate here consists of small changes to the original dataset, such as removing the
   'fnlwgt' feature  and records with missing or ill-formatted entries.

2. customer_segments.ipynb:
   In this project, we analyze a dataset containing data on various customers' annual spending amounts of diverse product categories for
   a wholesale distributor, then we apply KMeans (an unsupervised learning algorithm) to segment (do clustering) on the customers to get
   an idea of the different types of customers the wholesale distributor may interacts with. We first perform some data preprocessing
   steps: data analysis, feature scaling, and outliers removal. Then we apply PCA to reduce the dimensionality of the data (from 6 to 2)
   since some of the original data has correlationships hence a signifiant amount of variance can be explained by only two dimensions. 
   Finally we apply KMeans (after comparing pros/cons with Gaussian Mixsure Model) to segment the customers, analyze the customer
   types according to the segments and discuss how this information can be used by the wholesale distributor.

3. bike_rental.ipynb:
   Use public data set, perform data set cleaning, dataset analysis, and run different
   algorithms to predict the total number of bikes rent, then compare the result.
   Algorithms used includes: Linear Regression, Decision Tree, Random Forest.
   More descriptions are in the top cell of the Jupyter Notebook.

4. Housing.ipynb: 
   Use public data set, perform data set cleaning, dataset analysis, feature selection,
   and run Linear Regression and K fold cross validation to get final optimal predict value.
   More descriptions are in the top cell of the Jupyter Notebook.
