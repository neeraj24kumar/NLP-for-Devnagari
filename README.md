# NLP-for-Devnagari
A practical implementation of NLP processes such as tokenization, concordance, collocations, bigrams, stop words, and frequency/conditional frequency distributions

# Step-by-Step Guide for Natural Language Processing with Devnagari Text
This guide provides a comprehensive overview of how to perform Natural Language Processing (NLP) on Devnagari text using Python. The following steps will help you set up your environment, install necessary packages, and execute the provided Jupyter/ Colab Notebook (NLP_Devnagari.ipynb).

# Prerequisites
Before you begin, ensure you have the following files in your GitHub repository:
1. NotoSansDevanagari-VariableFont_wdth,wght.ttf - This font file (Font folder) is required to display Devnagari text correctly. 
2. पीला_वॉलपेपर_भोजपुरी.txt - This text file (Book folder) contains content in Bhojpuri, which will be used for NLP tasks.

Note :- provide proper path for the above mentioned files.

# Operations Covered:- 
### Tokenization
- **Definition**: The process of breaking down text into smaller units, such as words or sentences.
- **Purpose**: Facilitates the analysis of text by providing manageable units.
- **Types**:
  - **Word Tokenization**: Splits text into individual words.
  - **Sentence Tokenization**: Splits text into individual sentences.
- **Example**: The sentence "NLP is fun" becomes ["NLP", "is", "fun"].

### Concordance
- **Definition**: An index of words present in a text, along with their contexts.
- **Purpose**: Helps in understanding the usage and frequency of words.
- **Application**: Commonly used in literary analysis and lexicography.

### Collocations
- **Definition**: Pairs or groups of words that often appear together (e.g., "strong coffee" vs. "powerful coffee").
- **Purpose**: Identifies significant word pairings to understand language patterns.
- **Example**: "Data science" is a common collocation.

### Bigrams
- **Definition**: Pairs of consecutive words in a text.
- **Purpose**: Provide insights into the relationship between words.
- **Application**: Useful in various NLP tasks such as text generation and speech recognition.
- **Example**: In the sentence "NLP is fun", the bigrams are ["NLP is", "is fun"].

### Stop Words
- **Definition**: Commonly used words (e.g., "and", "is", "in") that are usually filtered out before processing text.
- **Purpose**: Removes words that provide little meaningful information to focus on more significant words.
- **Example**: Filtering out "is" and "in" from "NLP is in Kurla".

### Frequency Distributions
- **Definition**: The count of occurrences of each word in a text.
- **Purpose**: Understands the prominence and pattern of word usage.
- **Conditional Frequency Distributions**: Extends frequency distributions by considering the conditions or contexts of words.
- **Example**: In the sentence "NLP is fun. Learning NLP is essential.", the frequency distribution would count "NLP" twice.

### Conditional Operators
- **Definition**: Operators that perform different actions based on a given condition.
- **Purpose**: Implement logic in the analysis of text.
- **Example**: `if-else` statements in programming can be used to process text based on certain conditions.

### Regular Expressions (Regex)
- **Definition**: Sequences of characters that define a search pattern.
- **Purpose**: Enables pattern matching within text.
- **Application**: Useful for tasks like validating email addresses, finding and replacing text, and text parsing.
- **Example**: The regex `\b[A-Za-z]+\b` matches any whole word consisting of letters.
