#YouTube Video Recommender

##Data:
###We have used a Kaggle dataset which includes trending youtube videos.
###The link to the Dataset:- https://www.kaggle.com/datasets/datasnaek/youtube-new?select=USvideos.csv

##TF-IDF(Term Frequency-Inverse Document Frequency)
###TF-IDF is a text vectorization protocol which converts words in a document into vectors that then can be used in models
###As the first step of this project we are implementing TF-IDF with cosine similarity to rank the correlation between videos
###The data fed into TF-IDF is a concatenation of video title, description and tags.