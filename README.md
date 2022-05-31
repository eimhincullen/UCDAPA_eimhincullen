This project was undertaken as part of the UCD Professional Academy course Specialist Certificate in Data Analytics Essentials that took place from January 2022 to May 2022. This project was completed by Eimhin Cullen.

The aim of this project was to segment PGA Tour golfers into clusters using their strokes gained data from the 2021/2022 PGA Tour season up to the 23/05/2022. Strokes gained measures how the player is performing versus the field across four different aspects of the game. The second aim of this project was to generate insights into these clusters using the PGA Tour’s FedEx Cup rankings. 

The steps to this project can be split into the following five sections:
1.	Importing Data: This involved scraping the FedEx Cup rankings from the PGA Tour website and importing strokes gained data from a CSV file. 
2.	Merging Data: This involved reformatting a column and merging the two datasets together.
3.	Preliminary Analysis: This involved reviewing data completeness, filtering the data and exploring the relationship between the variables in the dataset.
4.	Machine Learning: This involved carrying out K-Means cluster analysis using the standardised strokes gained variables as the features. The clustering process was repeated with different combinations of features to optimise cluster quality. Hyperparameter tuning was used to identify the optimal number of clusters.
5.	Analysis and Insights: The clusters were visualised to help understand the unique characteristics of each. The cluster each player belongs to was added to the dataset and further insights were identified.

The submitted written report that contains detailed methodology, results and insights along with the jupyter notebook and csvs of the datasources can be found in this GitHub repository.
