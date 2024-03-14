# Computational Linguistics 1
## Academic Year Project 2019/2020

### Objective
Development of two Python programs that utilize the modules available in the Natural Language Toolkit to read two English text files, linguistically annotate them, compare them based on the required statistical indices, and extract the requested information.

### Implementation Phases
1. Choose and download in utf-8 plain text format two books of choice from those available on [Project Gutenberg](http://www.gutenberg.org/ebooks/).
2. Develop two programs that take the two files as input from the command line, linguistically analyze them up to Part-of-Speech tagging, and perform the required operations.

#### Program 1 
The program compares the two texts based on the following statistical information:
- Total number of sentences and tokens.
- Average length of sentences in terms of tokens and average length of words in terms of characters.
- Vocabulary size and distribution of hapaxes as the corpus grows in increments of 1000 tokens.
- Ratio of Nouns to Verbs.
- The 10 most frequent Part-of-Speech (PoS) tags.
- Extraction and sorting of the 10 PoS bigrams:
  - With maximum conditional probability, also indicating the relative probability.
  - With maximum associative strength (calculated in terms of Local Mutual Information), also indicating the relative associative strength.

#### Program 2 
For each of the two corpora, the program extracts the ten most frequent proper names and provides the following information for each name:
- The longest and shortest sentences containing the name.
- Extraction and ordering in descending frequency, also indicating the relative frequency:
  - The 10 most frequent Places.
  - The 10 most frequent People.
  - The 10 most frequent Nouns.
  - The 10 most frequent Verbs.
  - Dates, Months, and Days of the week extracted through regular expressions.
  - The longest sentence composed of a minimum of 8 tokens and a maximum of 12 with the highest probability, calculated through a Markov model of order 0 using frequency distributions extracted from the entire corpus of the book.

### Requirements
* Python 3.x
* NLTK library

### License
This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
