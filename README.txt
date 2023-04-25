data_cleaner.ipynb -- takes in the yelp dataset and divides it up into tokens that can be read by the BERT model
NewModel -- Iterates through label and vector files to create label and vector lists that can be concatenated by 
torch, then passes them into a neural network to train
gui.ipynb -- User interface that allows the user to type in a review and see the predicted star rating 
Label_Files -- Folder containing 625 files of bert model's output vectors
Vector_Files_2 -- Folder containing 625 files of bert model's output labels
