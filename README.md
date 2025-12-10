# Programming Assignment 1

## Frameworks Used

* **NLTK (Natural Language Toolkit)**: Used for standard tokenization and stopword removal.
* **TextBlob**: Used as a wrapper for simplified text processing.
* **SpaCy**: Industrial-strength NLP library used for efficient processing pipelines.
* **Pandas**: Used for data formatting and displaying comparison tables.

## Input & Output Files

### Input
* **`alice29.txt`**: The raw text file used for processing (source: Alice's Adventures in Wonderland).

### Outputs
After running the notebook, the following files will be generated:

1.  **`cleaned.txt`**: The preprocessed text (lowercase, no punctuation, no stopwords).
2.  **`words.txt`**: Contains two sections:
    * List of tokenized sentences.
    * List of tokenized words (stopwords removed).
3.  **`top10words.txt`**: A table showing the rank, word, and frequency of the top 10 most common words.
4.  **`time_compares.txt`**: A benchmark report comparing the average processing time of NLTK, TextBlob, and SpaCy (averaged over 10 loops).

## Author

* **Name:** Titipon Tawong
* **Student ID:** 662115013
* **Course:** NLP for Software Engineering