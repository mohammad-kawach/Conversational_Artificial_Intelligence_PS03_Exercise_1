# Title: Text Analysis with NLTK: Frequency Distribution Visualization

***

## Introduction:

This document outlines the process of analyzing text using the Natural Language Toolkit (NLTK) library in Python. We'll focus on creating a frequency distribution of tokens (words) in a sample text and visualizing the results with two plotting methods.

***

## Prerequisites:

    * Python 3.x installed
    * NLTK library (```pip install nltk```)
    * Matplotlib library (```pip install matplotlib```)

***

## Steps:

### Install and Import Libraries:
Install NLTK using pip install nltk.
Import necessary libraries:
    * nltk: For natural language processing tasks.
    word_tokenize from nltk.tokenize: To split text into words.
    * FreqDist from nltk.probability: To calculate word frequencies.
    matplotlib.pyplot as plt: For creating visualizations.

### Download Required NLTK Data:
    Use nltk.download('punkt') to download the tokenizer model for sentence segmentation.

### Create Sample Text:
    Define a string variable text containing the sample text you want to analyze.

### Tokenize the Text:
    Apply word_tokenize(text) to split the text into individual words (tokens).
    This stores the tokens in a list named tokens.

### Create Frequency Distribution:
    Use FreqDist(tokens) to create a frequency distribution object.
    This object tracks how many times each word appears in the text.

### Print Top 10 Most Frequent Tokens (Verification):
    Use a loop to iterate through the top 10 most common tokens (freq_dist.most_common(10)) and print their corresponding frequencies.

### Create and Display Plot (Built-in NLTK Method):
    Set the figure size using plt.figure(figsize=(12, 6)).
    Plot the frequency distribution using freq_dist.plot(20) (plots the 20 most frequent tokens).
    Add a title, labels, and rotate x-axis labels for better readability.
    Use plt.tight_layout() to prevent label cutoff.
    Display the plot using plt.show().

### Alternative Plot Using Matplotlib Directly:
    Create separate lists for words (words) and their frequencies (freqs) from the top 20 entries in the frequency distribution.
    Generate a bar chart using plt.bar(words, freqs).
    Add a title, labels, and rotate x-axis labels.
    Use plt.tight_layout() to prevent label cutoff.
    Display the plot using plt.show().

***

# Conclusion:

This code successfully demonstrates how to analyze text using NLTK and visualize the distribution of word frequencies. You can adapt this approach to analyze different text sources and explore other NLTK features for further text processing tasks.