# Portfolio - Numal Jayawardena

I'm a Data Scientist that used to work as a Software Engineer. I recently completed my Master of Management Analytics at Rotman (University of Toronto). Below are some of my personal Data Science projects as well as a few selected projects of the many that I completed as part of my master's program.

**NOTE:**
* Click on the project titles to see the Visualizations, insights drawn and the summary of the project
* If you would like to see the full process, each project also contains the full jupyter notebook 
    


## [John Mayer Lyrics Analysis using Natural Language Processing (NLP)](https://github.com/numalj/John-Mayer-Lyrics-Analysis "John Mayer Lyrics Analysis Notebook") 

This is a project that I came up with. Being a big fan of anything guitar related and John Mayer's music, I thought it would be interesting to analyze the lyrics of his songs/albums instead of getting distracted by those tasty guitar solos. See the gihub repo README file for a summary of the results.

* A [series of notebooks](https://github.com/numalj/John-Mayer-Lyrics-Analysis "John Mayer Lyrics Analysis Notebook") that use NLP techniques to analyze the lyrics used by John Mayer across his albums. 
* Analysis includes **sentiment analysis, topic modeling and analysis of vocabulary**.

See findings [here](https://github.com/numalj/John-Mayer-Lyrics-Analysis "John Mayer Lyrics Analysis Notebook")

## Time Series Forecasting model for Quarterly Stock Prices 

* Worked with my team mates at Rotman, to build a time series model that that identifies potential best performing stocks of the next quarter
* Scraped call transcripts for sentiment analysis (NLP) and used historical prices of stocks to train financial models from research papers.
* Models included Earnings Persistence and Residual Income Model


## [Medical Heart Beat Anomaly Classifier using LSTM](https://github.com/numalj/Hearbeat-Classification-LSTM)

Heart disease is a leading cause of death in Canada. Certain heart beat anomalies can be identified by listening to the pattern of 'lub'-'dub's in the heart beat. Using machine learning the task of identifying an anomaly can be automated in order to help unaware patients identify any hidden conditions and can also be used as pre-screening mechanism to help reduce load on the healthcare system.

* Preprocessed and Augmented audio files to create a larger training set, since there was a very limited set of available 
* Built a RNN + LSTM model to classify heart beat sounds with 65% sensitivity
* The audio files had to be converted to mfcc format so that they could be used in our model


## [Ebay Competitive Auction Classifier - Decision Trees](https://github.com/numalj/BigDataAssignments/tree/master/ebayDecisionTrees)

This project is an exercise in using Decision Trees with past ebay auction data to try and predict whether an auction would be competitive or not. Based on the decision tree splits, recommendations were provided with general guidelines to follow when setting up the auction to give the user a more competitive chance. See the [project page](https://github.com/numalj/BigDataAssignments/tree/master/ebayDecisionTrees) for diagrams and more details.


## Hot Dog or Not?

This project tries to classify whether an image is a hot dog or not a hot dog. It's based on an scene from the TV show 'Silicon Valley'. 

* Trained a **CNN (Convolutional Neural Network)** to try and classify images
* Since the hot dog data set was small, used **transfer learning** and experimented with pretrained models Inception and Mobilenet
* Used tensorflow to help debug errors


## [Yelp Review Sentiment Analysis](https://github.com/numalj/YelpReviewAnalysis)

This project scrapes the Yelp website to extract customer reviews of restaurants and builds a data set. The data set was used to train a Naive Bayes classifier that uses Sentiment Analysis to predict whether a review is positive (more than 3 stars) or negative (less than 3 stars). 


**Potential use cases:**

    1. The ratio of positive to/negative reviews can also be monitored enabling quality control of the restaurant.
    2. This sort of model can be used to clasify future reviews so that when the number of reviews is very high, 
       common themes in the negative reviews can be extracted and addressed much faster. 
    3. Reviews can be further broken down into categories such as location and cusine.
       This can provide insight into locations that might have low barriers to entry because none the 
       existing restaurants are satisfying the majority of customers
    4. Finding insights about what about restaurants people like and dislike


## [Computer Time Tracking App in Python](https://github.com/numalj/PythonTimeTracker)

When we are sitting down at our computer, it is easy to lose track of time and suddenly you're wondering where all your time went. This is an ongoing personal project of mine. I thought it would be interesting to have an application track what apps and websites you spend your time on. This app collects data, which can then be analysed for more insight and to take action on.

* Used Object Oriented Programming practices to build this Python App
* Google Chrome activity is monitored on a per url basis, showing how much time was spent on each web domain
