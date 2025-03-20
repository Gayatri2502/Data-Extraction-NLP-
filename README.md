Data Extraction and NLP 


The objective of this assignment is to extract textual data articles from the given URLs and perform text analysis to compute variables as specified in the instructions.

Solution Overview
This solution involves the following steps:
1. Data Extraction: Extract article text from provided URLs.
2. Text Analysis: Perform various text analysis tasks including sentiment analysis, readability analysis, and calculating other specified variables.
3. Output Generation: Save the analysis results in the specified format.

Libraries Used

The solution utilizes the following Python libraries:
- `requests`: For making HTTP requests to fetch web pages.
- `BeautifulSoup`: For parsing HTML content and extracting article text.
- `nltk`: Natural Language Toolkit for tokenization, cleaning text, and various text analysis tasks.
- `pandas`: For organizing and manipulating data in a tabular format.

Folder Structure

The folder structure is organized as follows:
- main.ipynb: Contains the Python script for data extraction and analysis.
- stopwords: Contains files with stop words used for cleaning text.
- sentiment_words: Contains files with positive and negative words used for sentiment analysis.
- input: Contains the input CSV file (`Input.csv`) with URLs.
- extracted_texts: Contains the extracted article text saved as individual text files.
- requirements.txt: Lists all Python dependencies required for running the solution.

Instructions for Running the Solution

1. Environment Setup:
   - Ensure Python 3.x is installed on your system.
   - Install required dependencies by running `pip install -r requirements.txt`.

2. Input Preparation:
   - Place the input CSV file (`Input.csv`) containing URLs in the `input` folder.

3. Running the Solution:
   - Open a terminal or command prompt.
   - Navigate to the directory containing the solution files.
   - Execute the Python script `main.py` by running `python main.py`.

4. Output Retrieval:
   - Once the script completes execution, find the generated output file named `Output_Data.xlsx` in the main directory.
   - Extracted article text is saved in the `extracted_texts` folder.

Notes

- Ensure stable internet connectivity for fetching URLs.
- In case of errors or exceptions during execution, check the console output for detailed error messages.

---

Please let me know if any further clarification or assistance is needed.
