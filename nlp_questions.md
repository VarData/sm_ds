### Lemmetizer
### Tokenizer



### What is POS Tagger?
1. http://cs.stackexchange.com/questions/14037/word-classification-algorithms/27857#27857
2. http://www.cs.umd.edu/~nau/cmsc421/part-of-speech-tagging.pdf
3. http://www.katrinerk.com/courses/python-worksheets/hidden-markov-models-for-pos-tagging-in-python


### What is Parser in NLP? Describe in details?
A natural language parser is a program that works out the grammatical structure of sentences, for instance, 
which groups of words go together (as "phrases") and which words are the subject or object of a verb. 
Probabilistic parsers use knowledge of language gained from hand-parsed sentences to try to produce the most likely analysis of new 
sentences. These statistical parsers still make some mistakes, but commonly work rather well. Their development was one of the biggest 
breakthroughs in natural language processing in the 1990s.


### What ML methods have you used?
Linear Regression
Logistic Regression
Random Forrest
Decision Tree

### What nlp project pipeline?

### Decribe your project and your role in it?


### What does tf-idf mean?
Tf-idf stands for term frequency-inverse document frequency, and the tf-idf weight is a weight often used in information retrieval and text mining. This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. 
The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus. 
Variations of the tf-idf weighting scheme are often used by search engines as a central tool in scoring and ranking a document's relevance given a user query.
One of the simplest ranking functions is computed by summing the tf-idf for each query term; many more sophisticated ranking functions are variants of this simple model.
Tf-idf can be successfully used for stop-words filtering in various subject fields including text summarization and classification.

### How to compute TF-IDF?
Typically, the tf-idf weight is composed by two terms: the first computes the normalized Term Frequency (TF), aka. the number of times a word appears in a document, divided by the total number of words in that document; the second term is the Inverse Document Frequency (IDF), computed as the logarithm of the number of the documents in the corpus divided by the number of documents where the specific term appears.
•	TF: Term Frequency, which measures how frequently a term occurs in a document. Since every document is different in length, it is possible that a term would appear much more times in long documents than shorter ones. Thus, the term frequency is often divided by the document length (aka. the total number of terms in the document) as a way of normalization: 

TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document).
•	IDF: Inverse Document Frequency, which measures how important a term is. While computing TF, all terms are considered equally important. However it is known that certain terms, such as "is", "of", and "that", may appear a lot of times but have little importance. Thus we need to weigh down the frequent terms while scale up the rare ones, by computing the following: 

IDF(t) = log_e(Total number of documents / Number of documents with term t in it).
See below for a simple example.

### Example:
Consider a document containing 100 words wherein the word cat appears 3 times. The term frequency (i.e., tf) for cat is then (3 / 100) = 0.03. Now, assume we have 10 million documents and the word cat appears in one thousand of these. Then, the inverse document frequency (i.e., idf) is calculated as log(10,000,000 / 1,000) = 4. Thus, the Tf-idf weight is the product of these quantities: 0.03 * 4 = 0.12.

