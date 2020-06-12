# STATS170-Project

* user.csv
* ML Model.ipynb	
* ModelWithEvaluation.ipynb	
* Visualization.twb	

9 features for our models: 
user’s attitude to the news, user’s age, user’s gender, reliability level for the News source, number of coronavirus confirmed case, number of how many years the account has been created, number of users this account is following, number of followers of this account, state name.


	
Files in More Datails Folder:
* get_data.ipynb：Get “Tweet Status” object from Twitter for developers to use. (e.g: Tweets id, user’s profile, tweets text, retweeted_status, and etc.
* ProcessingData.ipynb，Add_newslinks.ipynb，Add_newstext.ipynb：Open urls as html object. Input is url, and output is all the information on the webpage, such as title, text, ect.
* Add_RealFake.ipynb：label news as Fake and Real
* Add_GAFeature.ipynb: Use the detector to detect users’ age and gender based on their profile images and store them in the datasets.
* Add_ReliabilityLevel.ipynb: Get news sources from News API’s news source collection. (News sources are ABC, BBC, and etc.) And give a classification of source reliability for each tweet based on it.
* Add_accountAge.ipynb: Count account age and add it as a feature in the datasets.
* Add_covidFeature.ipynb: Add confirmed number of coronavirus as a feature in the datasets.
* Flow.tfl: Combine Confirmed, Death, Recovered datasets to one and reform its as the coronavirus datasets structure for better use.
* Coronavirus dataset
