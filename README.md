# NLP
NLP - Classification Example

https://raw.githubusercontent.com/franciscadias/data/master/stack-overflow-data.csv

The dataset has two columns. ‘post’ column consists of the different posts which are registered on stack overflow. ‘tags’ column represents the language to which the post is related. Number of rows: 40,000

1.) Print the Data description
2.) Create a dataframe with two columns ‘post’ and ‘tag’. check the head, info, and describe methods on the dataframe

3.) Remove punctuations and stopwords from the text in the ‘post’ column

4.) Create two objects X and y. X will be the ' post’ column of the above dataframe and y will be the ' tag' column. Create a CountVectorizer object and split the data into training and testing sets. Train a Multino mialNB model for classifying the tag label of reviews and Display the confusion Matrix (5 Marks)[Creating Multinominal NB model is higher complexity Question. To get full marks it must be addressed properly ]

5.) Display the HMM POS tagging on the first 4 rows of ‘post’ 
