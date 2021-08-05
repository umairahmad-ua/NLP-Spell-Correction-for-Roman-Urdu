# NLP-Spell-Correction-for-Roman-Urdu
In this work, I have developed spell correction for Roman Urdu. 
This works deal with correcting non-word errors using the Noisy Channel model. This spell correction technique has been widely used by word processors
and is also being used by Google in its search engine. Whenever you type in a query with a misspelled word such as corection Google would instantly return the results for correction instead.
# Background 
In this work, I have implemenedt a spell correction program for Roman Urdu in Python. Spell correction
using the Noisy Channel model is based on Bayes Theorem. Where w is the candidate
word and x is the misspelled word.
# Data
This code requires two files data.txt which will serve as the corpus and misspellings.txt for generating
error model tables. Make sure that you have access to both files before starting available in this repo with the name "DataSet".

1. data.txt is a collection of Roman Urdu sentences
2. misspellings.txt contains a list of words and their misspellings
