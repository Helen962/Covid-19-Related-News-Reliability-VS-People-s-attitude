# STATS170-Project

Jupyter Notebook files to run the machine learning model
* user.csv: sample dataset for running the model, Dimensionality: 39805 rows × 12 columns	
* ML Model.ipynb：KNN model and random forest model (OUR MAIN NOTEOOK)	
* ModelWithEvaluation.ipynb: models with evaluation part	
* Visualization.twb: data visualization part with Tableau 	

9 features for our machine learning models: 
user’s attitude to the news, user’s age, user’s gender, reliability level for the News source, number of coronavirus confirmed case, number of how many years the account has been created, number of users this account is following, number of followers of this account, state name.

Output for our models: 
Real/Fake

# Steps to run Machine Learning Model (without evelation and discussion of the machine model):
1) Download the data file "user.csv"
2) Open the "ML Model.ipynb" file 
3) Change the path of "user.csv" data
4) Run the script line by line



# Steps to run Machine Learning Model with evelation and discussion of the machine model:
1) Download the data file "user.csv"
2) Open the "ModelWithEvaluation.ipynb" file 
3) Change the path of "user.csv" data
4) Run the script line by line
5) You can find the method we used to explore data features, and how we adjusted the parameters for KNN and Random Forest.


	
Files in "More Datails" Folder:
* get_data.ipynb：Get “Tweet Status” object from Twitter for developers to use. (e.g: Tweets id, user’s profile, tweets text, retweeted_status, and etc.
* ProcessingData.ipynb，Add_newslinks.ipynb，Add_newstext.ipynb：Open urls as html object. Input is url, and output is all the information on the webpage, such as title, text, ect.
* Add_RealFake.ipynb：label news as Fake and Real
* Add_GAFeature.ipynb: Use the detector to detect users’ age and gender based on their profile images and store them in the datasets.
* Add_ReliabilityLevel.ipynb: Get news sources from News API’s news source collection. (News sources are ABC, BBC, and etc.) And give a classification of source reliability for each tweet based on it.
* Add_accountAge.ipynb: Count account age and add it as a feature in the datasets.
* Add_covidFeature.ipynb: Add confirmed number of coronavirus as a feature in the datasets.
* Add_userAttitude.ipynb: Add user's attitude by analyzing their tweets' text.
* Flow.tfl: Combine Confirmed, Death, Recovered datasets to one and reform its as the coronavirus datasets structure for better use by Taleau Prep.
* Coronavirus dataset

