## CUISINE-CHATBOT
Retrieval based chatbot is build to give information of various cuisine using TF-IDF Vectorizer. The data collected from Wikipedia page Cuisine. WordNet corpus is used in text processing.

### STEPS INVOLVED
1) IMPORT LIBRARIES: nltk, TfidfVectorizer (similarity matrix which incoporates relative frequency of terms across possible responses), string, random, bs4, cosine_similarity(match vectors), request and re
2)  DOWNLOAD RESOURCES : punkt, wordnet corpus from nltk
3)  DATA COLLECTION: using requests library,cuisine( a wikipedia article) is return.
4)  Beautify the textual data using beautiful soup library.
5)  Get rid of special characters and empty spaces using regular expressions(re) from text.
6)  Convert text into sentences and words using nltk library.
7)  Some greeting responses are generated for some predefined greeting inputs.
8)  Preprocessing with Punctuation Removal and Lemmatizing.
9)  Language Modeling with tf-idf
