# starststar
ArtificialIntelligence

Please read the Power Point file (Data Science with R.pptx) to understand the aim and process.
Create the database and tables in SQL Server before running the code. The script to create the database is named CreateDatabase.sql. The script to create the tables in database is named TablesToAnalyze.sql.
The extracted data from Twitter are in the csv files named; MotherTeresa.csv, BarackObama.csv, DonaldTrump.csv.
The saved model after it was trained is named modelTrainingWithGlmnet.RDS.
The original data that was used to train the model is named TrainingData.csv. It was retrieved from from http://help.sentiment140.com/for-students/. The data was cleansed to remove invalid IDs.

The data retrieval from Twitter was inserted into the database. However when the code is executed, new data will be retrieved. The new data can be inserted into the database. The new data must be inserted with only the following four columns; 
OpinionId (int) identity (1,1), 
userno(varchar(50), 
diction(varchar151), 
ResponseDate (date)

My work-in-progress is to cleanse the data that was retrieved from Twitter, and correct the changing colors of the legend.

References:
Bryl, S. Twitter sentiment analysis with R. (2014). http://analyzecore.com/2017/02/08/twitter-sentiment-analysis-doc2vec/
Bryl, S. Twitter sentiment analysis with Machine Learning in R using doc2vec approach (part 1). (2017). http://analyzecore.com/2014/04/28/twitter-sentiment-analysis/

