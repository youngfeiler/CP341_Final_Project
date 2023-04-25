data_cleaner.ipynb -- takes in the yelp dataset and divides it up into tokens that can be read by the BERT model
NewModel -- Iterates through label and vector files to create label and vector lists that can be concatenated by 
torch, then passes them into a neural network to train
gui.ipynb -- User interface that allows the user to type in a review and see the predicted star rating 
Label_Files -- Folder containing 625 files of bert model's output vectors
Vector_Files_2 -- Folder containing 625 files of bert model's output labels

Using BERT to classify yelp reviews 

Using the pretrained bert downloaded from the internet, we wanted to see how effectively we could classify 
yelp reviews by their attached star ratings using sentiment analysis. 
We did this by passing tokenized review text from our dataset through bert, which then produced vectors that
were saved into files and passed into our neural network. Our neural network then took in the vectors produced 
by bert. After training on the dataset, our model produced a value of 0 or 1, with 1 corresponding to a 
favorable review and 0 corresponding to an unfavorable review. 
