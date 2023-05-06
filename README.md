# The State of Natural Language Processing
Textual analysis of the works of social contract theorists Thomas Hobbes, John Locke and Jean-Jaques Rousseau

## Metadata
```
Author: Linnaea Kavulich
Contact: qpk4kp@virginia.edu
Course: DS5001 Spring 2023
```

## COURPUS
```
This analysis includes the following works
```
| Title | Author | Box URL |
| :- | :- | :- |
| The Social Contract | Jean-Jacques Rousseau |  https://virginia.box.com/s/vd98kfw7bjil1ejx8z4euyuyf8ggwfss
| Leviathan | Thomas Hobbes | https://virginia.box.com/s/mbsrflus3gq93ekebkshlbigpuvguaty
| Second Treatise of Government | John Locke | https://virginia.box.com/s/2jdhmo4o62td34xiojm90jh0pu39w5fn
| Discourse on the Origin and Basis of Inequality Among Men | Jean-Jacques Rousseau | https://virginia.box.com/s/976k8neitf41mwaav5sl3o4334xseqvv
| An Essay Concerning Humane Understanding, Vol. 1 | John Locke | https://virginia.box.com/s/vpun69jcpxmb75wrci77up5nyuwh3yo9
| An Essay Concerning Humane Understanding, Vol. 2 | John Locke |  https://virginia.box.com/s/f8aezwai61m17gw4khnmzp2qfyvc4yzj ||

**Table 1:** metadata for corpus

## Pipeline
```
Notebooks were created in the followin order for the following aims
```
| Title | Purpose | 
| :- | :- |
| VOCAB_CORPUS_LIB.ipynb | Loads and parses source files, outputs LIB, CORPUS, VOCAB tables
| TFIDF_DFIDF.ipynb | Appends VOCAB and CORPUS with DF-IDF and TF-IDF
| PCA.ipynb | Principal component analysis 
| LDA.ipynb | Topic modeling 
| word2vec.ipynb | Generates word embeddings
| sentiment.ipynb | Sentiment analysis 
| FINAL_REPORT.ipynb | Notebook with relevant figures and analysis ||

**Table 2:** notebook pipeline
