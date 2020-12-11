# Cosine Similarity between two similar sentences
Text pre-processing - Removing stop words and punctuations -Stopwords - and, is, are, at, etc. Punctuationa - “” ,  . ? ! etc. 
Transforming all words to lower case  - GREAT , Great , great -  great 
Stemming in NLP is simply transforming any word to it’s base stem ( set of characters that are used to form the word and it’s derivative ) - tune , tuning ,tuned - tune
Word tokenization - Separating a piece of text into smaller units called tokens. 
Text Vectorization -
Machine learning and NLP algorithms can’t work with raw text directly. The text must be converted into numbers, specially vectors of numbers. 
Ex -  Review 1 : This movie is very scary and long.           Review 2 : This movie is not scary and slow.  
Cosine Similarity - 
It is basically makes use of the cosine of the angle between two vectors. Based on that, it will tell us if those two vectors are close.
The dot product of two vectors is v . w
If β is the angle between them, then cos β =   ( v . w ) / || v || || w || 
The cosine similarity is proportional to the similarity between two vectors that we are comparing.
cosine  ∝  similarity
Ex - Sentence 1 - Liberalism stood for the equality of markets in the economic sphere and for the elimination of the limits imposed by the state on the flow of goods and resources.
     Sentence 2 - The term liberalization refers to the process in which a state removed all the restrictions on the private activities of the individual.
		                      cosine similarity is - 0.7431235670555499
