# Spell_Checker
Create a spell checker: correct spelling of a corrupted word.

Steps:
1. Train a language model on training data. 
2. Use model to predict the outputs (correct spelling) for the test data (corrupted words). 

Data Description: 

Training Datasets: 

big.txt: 
This file consists of lot of text. We can use this file to collect information about words. Number of occurrences of word. 

spell-errors.txt: 
The format of every line in this text is the correct word is specified followed by the misspelled words. 
For example, like "raining: rainning, raning". Form the 4 confusion matrices from this data set. 

count_1w.txt & count_2w.txt:
count_1w.txt has text in the format: and count_2w.txt has text in the format: . 
We can make use of these datasets to create much better models. 

