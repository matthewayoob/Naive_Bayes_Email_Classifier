# Naive Bayes Email Classifier

ABOUT THE DATA --
 Inside the 'data' folder, the emails are separated into 'train' 
and 'test' data. Each of these folders has nested 'spam' and 'ham'
folders, each of which has a collection of emails as txt files.
You will only use the emails in the 'train' folder to train your 
classifier, and will evaluate on the 'test' folder.
        
The emails we are using are a subset of the Enron Corpus,
which is a set of real emails from employees at an energy
company. The emails have a subject line and a body, both of
which are 'tokenized' so that each unique word or bit of
punctuation is separated by a space or newline. The starter
code provides a function that takes a filename and returns a
set of all of the distinct tokens in the file.
