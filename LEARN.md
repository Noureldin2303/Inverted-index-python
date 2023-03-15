# Inverted-index-python
Writing a simple Inverted Index in Python

## What is an Inverted Index?

```
The Inverted Index is the data structure used to support full text search over a set of documents.
It is constituted by a big table where there is one entry per word in all the documents processed,
along with a list of the key pairs: document id, frequency of the term in the document.
```

## How does it work?

   
* Collect the documents to be indexed – I will use simple strings for while;
* Tokenize the text, turning each document into a list of tokens
* Do linguistic preprocessing, producing a list of indexing terms
* Index the documents that each term occurs in by creating an inverted index, consisting of a dictionary and postings.

--------------------------------------------------------------------------------------------------

### For Example:


![inverted index](https://hdscorp--c.na74.content.force.com/servlet/servlet.ImageServer?id=0151J000004MM9EQAW&oid=00Do0000000IJig)
