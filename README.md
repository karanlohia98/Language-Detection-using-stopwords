# Language-Detection-using-stopwords
I have used a dataset containing 10 different languages and classified them using stopwords included in nltk library.
Chinese Mandarin ,Hebrew and Japanese were not classified as there were no stopwords found for them in the nltk library.
In this work we presented analysis using Stop words for language detection.
We find that a large source of error is due to some European languages having the same vocabulary while been differentiated on the terms of grammar and pronunciation.
To successfully classify these languages we need to understand the underlying grammar that differentiates them. 
The accuracy comes out to be 64.437%.
The reason for this low accuracy is that German and Dutch languages have the same vocabulary, hence they cannot be classified using the available stop words.

