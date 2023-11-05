# Dictionary API
A simple web-based dictionary API built with Flask and pandas.

# Introduction
The Dictionary API allows users to retrieve definitions for words from a provided dataset. The web interface displays a list of words from the dataset and guides the user on how to fetch definitions using the API endpoint.

# Setup and Installation
## Requirements:
Python
Flask
pandas

## Steps:

1. Clone the repository or download the source code.

2. Navigate to the project directory in the terminal.

3. Install the required packages:

   pip install Flask pandas

4. Run the Flask app:

   python <filename>.py

  Replace <filename>.py with the name of your main Python script.

# Usage
## Web Interface:

Navigate to http://127.0.0.1:5001/ in your browser.

1. You'll see a list of words available in the dictionary.
2. There are instructions on how to retrieve the definition of a word using the API endpoint.
   
## API Endpoint:

To fetch the definition of a word, use the following format:

http://127.0.0.1:5001/api/v1/<word>/

Replace <word> with the desired word from the list. For example:

http://127.0.0.1:5001/api/v1/sun/

The API will return a JSON response with the word and its definition.

# Notes

1. The current dataset is sourced from dictionary.csv. Ensure the CSV has columns named "word" and "definition".
   
2. This is a simple implementation and may not handle large datasets efficiently.
   
3. The API currently does a case-sensitive search. Ensure you input the word with the correct casing.

5
