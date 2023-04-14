# Email_Spam_Detection



CountVectorizer is a class in scikit-learn that is used to convert a collection of text documents into a matrix of token counts. It does this by:

Tokenizing the text: splitting it into individual words or tokens.
Counting the frequency of each token in each document.
Creating a matrix where each row represents a document and each column represents a token, and the values represent the frequency of each token in each document.

The dump() function from the pickle module is used  to write the object to a binary file in the local file system.

Why is Multinomial Naive Bayes Best for Email Spam Detection:
a)Multinomial Naive Bayes (MNB) is a popular algorithm for email spam detection because it works well with text data that has a high dimensionality.
b)MNB assumes that the frequency distribution of the words in spam emails is different from that of non-spam (ham) emails
