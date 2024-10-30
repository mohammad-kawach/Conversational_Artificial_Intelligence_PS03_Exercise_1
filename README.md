# NLTK Text Tokenization Project

## Description
This project demonstrates basic text tokenization and frequency analysis using NLTK (Natural Language Toolkit) in Python. The notebook contains code for tokenizing text, analyzing token frequencies, and visualizing the results using matplotlib.

## Features
- Text tokenization using NLTK
- Token frequency analysis
- Frequency distribution visualization
- Basic text cleaning (lowercase conversion and punctuation removal)

## Prerequisites
- Python 3.x
- Google Colab or Jupyter Notebook
- Required libraries:
  - nltk
  - matplotlib

## Installation
```bash
pip install nltk
```

## Usage
1. Open the notebook in Google Colab or Jupyter Notebook
2. Run the cells in sequence
3. The code will:
   - Tokenize the provided text
   - Calculate token frequencies
   - Generate visualization of token distribution
   - Provide cleaned token analysis

## Sample Output
- List of tokens
- Frequency distribution of tokens
- Bar plot of token frequencies
- Cleaned token analysis

## Code Structure
```python
# Install NLTK
!pip install nltk

# Import libraries
import nltk
from nltk.tokenize import word_tokenize
from nltk.probability import FreqDist
import matplotlib.pyplot as plt

# Download NLTK data
nltk.download('punkt')
```

## Exercise Details
This code was created as part of the "Conversational AI: History, Applications, Future" course (WiSe_24/25) under Dr. Svetlana Meissner.

## Author
Mohammad Kawash

## License
This project is available for educational purposes.