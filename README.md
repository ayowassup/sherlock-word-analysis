# Word Frequency Distribution in "The Adventures of Sherlock Holmes"

This Python project analyzes the word frequency distribution in "The Adventures of Sherlock Holmes," a classic novel by Sir Arthur Conan Doyle. The project leverages web scraping techniques, natural language processing (NLP), and data visualization to gain insights into the most frequently used words in the text.

## Project Overview:

1. **Web Scraping:** Fetching the novel from Project Gutenberg.
2. **HTML Parsing and Text Extraction:** Processing HTML content to obtain plain text.
3. **Tokenization and Lowercasing:** Breaking down the text into individual words and converting them to lowercase.
4. **Stopword Removal:** Filtering out common English stopwords.
5. **Word Frequency Analysis:** Counting the occurrences of each word.
6. **WordCloud Visualization:** Generating a WordCloud of the top 20 words.
7. **Bar Graph Visualization:** Creating a detailed bar graph of the word frequency distribution.

## Used Libraries:

- `requests`: For making HTTP requests and fetching web content.
- `BeautifulSoup` from `bs4`: A library for web scraping, parsing HTML, and text extraction.
- `nltk` (Natural Language Toolkit): For natural language processing tasks, including tokenization and stopwords.
- `collections.Counter`: For counting word occurrences.
- `pandas`: For data manipulation (not extensively used in this project).
- `matplotlib.pyplot`: For plotting visualizations.
- `WordCloud`: For generating WordCloud visualizations.

## Project Output:

The final output includes a list of the top twenty most frequent words, a WordCloud visualizing the top twenty words, and a bar graph providing a detailed representation of the word frequency distribution.

## How to Use:

1. Clone the repository.
2. Open the Jupyter notebook (`Word Frequency Distribution in Sherlock Holmes Novel.ipynb`) in your preferred environment.
3. Run the notebook cells to execute each step of the project.
