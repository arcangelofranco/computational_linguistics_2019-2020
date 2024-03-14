# Comprehensive Text Analysis Toolkit

This Python scripts, `program_1.ipynb` and `program_2.ipynb`, provides a comprehensive suite of tools for advanced text analysis using the NLTK library. It offers a wide range of functionalities to deeply analyze textual data, including:

## Text Analyzer 1 - `program_1.ipynb`

- **Basic Text Analysis:**
  - Total number of tokens.
  - Total number of sentences.
  - Average sentence length.
  - Average word length.
  - Number of hapax legomena.
  - Incremental frequency of tokens.
  - Noun-to-verb ratio.
  - Top 10 most frequent bigrams.
  - Bigrams with Conditional Probability.
  - Bigrams with Associative Strength (LMI).

## Text Analyzer 2 - `program_2.ipynb`

- **Advanced Text Analysis:**
  - Top 10 most frequent proper nouns (NNP).
  - Longest and shortest phrases for each top proper noun.
  - Top 10 GPEs (Geographical Entities) in sentences with top nouns.
  - Top 10 proper names (PERSON) in sentences with top nouns.
  - Top 10 most frequent nouns (NN, NNS, NNP, NNPS) in sentences with top nouns.
  - Top 10 most frequent verbs (VBD, VBG, VBN, VBP, VBZ) in sentences with top nouns.
  - Dates, months, and days mentioned in sentences with top nouns.
  - Phrase with the highest probability using a Markov Model of Order 0 based on top noun occurrences.

## Features

- **Basic Text Analysis:**
  - Calculate various metrics such as token count, sentence count, and average lengths.
  - Analyze the distribution of hapax legomena and incremental frequency.
  - Determine the noun-to-verb ratio and identify top bigrams.
  - Explore bigrams with conditional probability and associative strength.

- **Advanced Text Analysis:**
  - Discover most frequent proper nouns and phrases containing them.
  - Extract geographical entities and proper names from sentences.
  - Analyze the frequency of nouns and verbs in context with top nouns.
  - Identify dates, months, and days mentioned in the text.
  - Predict probable phrases using a Markov Model based on top noun occurrences.

## Usage

1. Ensure you have Python installed on your system.
2. Run the script with your text files as input.
3. View the results in the specified output file.
