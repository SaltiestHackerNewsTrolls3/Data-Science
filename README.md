# Data-Science

The Data Science team for this project was able to accomplish data collection, cleaning, and scoring of the comments. The BQ_Hacker_New_Grp3.ipynb details our attempts to use google big query to pull what data we could. The Cleaning-Scoring.ipynb details the steps taken to clean the data, including removing urls, html markers wrapped in <> and a few others, along with lemmatizing the text to ensure the widest net could be cast by our sentiment analysis technique. 
We chose to use the Vade lexicon with NLTK's sentiment analyzer module. It proved to be decently effective, but upon further research, was among the best not made from scratch solutions. We did attempt to make one, but unfortunately, with no labeled data, the time investment proved out of scope.
