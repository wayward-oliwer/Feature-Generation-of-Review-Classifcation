# Feature Generation of Review Classification
This software was made during my Natural Language Processing module.
It involved using a database of 2,000 positive reviews and 2,000 negative reviews. 
This database was then split between training, validation and testing data sets. 
The split selected was 70:20:10 as natural language processing requires heavy training for maximised accuracy and therefore 70% of the data was used in the training.

Different methods of tokenisations were used, such as white space separation, stemming and lemmatiziation.
These methods were then put through different methods of filtering to see which combination allowed from the most optimal tokenisation method.
The features of the filtering were refined by removing common words and words of short lengths and using TF-IDF as the value of each term within a review. 

The classification approach for this coursework was the Naive-Bayes approach and my implementation was later compared with the implementation in the SkLearn library. 
My implementation ended up being on par with the SkLearn library's implementation.

This software was written in Python through the use of Jupyter Notebook.
