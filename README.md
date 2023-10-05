
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Semantic Folding Project

## By: Saul Varshavsky


### Sources

https://dzone.com/articles/introduction-to-word-vectors 

https://www.geeksforgeeks.org/word-embeddings-in-nlp/ 

https://github.com/nitinkaushik01/Natural_Language_Processing/blob/master/Word_Embedding_using_word2Vec.ipynb 

https://youtu.be/ZogxNcyqVqE?si=gy7sFLZXilqAJU3D 

https://youtu.be/8_bSgFUwpjw?si=Kw5CG4CQJGjNEiF7

https://youtu.be/sZGuyTLjsco?si=7TK19x18fFYOLXg_ https://youtu.be/uszt88Z-0Fc?si=FfsCrJy0Ank2m6s3 

https://medium.com/@marcusa314/visualizing-words-377624cb20c7 

https://youtu.be/YcSTKEHS9Es?si=FKPdHONon28OmqDu 

https://youtu.be/39w4WSxvRQM?si=HWMGXoTLELAw-cEN


<!-- badges: start -->
<!-- badges: end -->

### Project Description

This project aims to create a basic Semantic Folding model using other models, mainly
Word Vector and Word Embeddings.

### Background Information

A Semantic Folding model is a model that takes in a single word or multiple words
as input to produce a fingerprint that uniquely represents the given word(s).
In order to setup the model, the model gets fed a large article/document and from there forms
clusters of words (i.e. each word gets assigned coordinates which determine its location) closely 
related along an n-dimensional space. These clusters help take into account the appropriate contexts of words
given the input provided. Using this idea, the fingerprint represents all the coordinates of the words provided as input
along with other words that are closely related based on the clusters initially formed.




### Requirements to Use the Code

The following packages have been used for writing all the code:

1) pandas
2) numpy
3) string
4) nltk
5) gensim
6) networkx
7) karateclub
8) matplotlib
9) keras


### Data Used

The csv file "SemanticFoldingData.csv" was used for this project. This data includes information about the text of a
given article/document, as well as which site it was retrieved from. Since the theory behind a Semantic Folding model is to
not have it be used on massive amounts of data but rather only one document of text, the data used for this project
therefore contains information for only one article.
