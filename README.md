# Extractive Text Summarization using Sumy

This repository contains a Python script for performing extractive summarization using the Sumy library. Extractive summarization involves selecting and condensing important information from a given text. In this script, we use the LexRank algorithm provided by Sumy to generate an extractive summary.

## Installation

Before running the script, make sure to install the necessary libraries. You can do this by running the following command:

```python
pip install sumy nltk
```
Additionally, download the required NLTK data by executing:
```python
python -m nltk.downloader punkt
```
## Usage
To perform extractive summarization, use the extractive_summarization function in the script. Provide the input text and the desired number of sentences for the summary. 
Below is an example:
```python
# Give input text
input_text = """Your input text here"""

# Set the number of sentences you want in the summary
num_summary = 2

# Perform extractive summarization
summary_result = extractive_summarization(input_text, num_summary)

# Print the result
print("Original Text:")
print(input_text)
print("\nExtractive Summary:")
print(summary_result)
```

## Acknowledgments
This script uses the Sumy library for extractive summarization. For more information on Sumy, refer to [Sumy Documentation](https://pypi.org/project/sumy/).
