# UTIR-Sentiment-Analysis

### Dataset
The data set can be dowloaded from https://ai.stanford.edu/~amaas/data/sentiment/.
The folder contains training and test data split up into postiive and negative reviews where the rating for each review is from the file name in the format:
[[id]_[rating].txt]

### Instructions
First run 'Combine AclImdb Folder Reviews and Scores' in order to consolidate the positive and negative reviews into a new text file for each testing and training dataset. Additionally the code takes the IMDB rating from the file names and creates a new file with all the ratings. These new files can then be used in 'IMDB Sentiment Analysis' 
to be used in the model.

### Resources
<li>https://towardsdatascience.com/sentiment-analysis-using-lstm-step-by-step-50d074f09948
