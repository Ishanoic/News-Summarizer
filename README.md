# News-Summarizer


# News Summarization App

## Overview
This Streamlit app provides a user-friendly interface for summarizing news articles. It fetches news articles from various categories and generates a summary of the selected article using the Pegasus model from the Hugging Face Transformers library.

## Features
- Select a topic from a list of categories such as Politics, Tech, Sports, Business, etc.
- Fetch news articles from the selected category.
- Display a list of news articles along with their titles, summaries, and URLs.
- Generate the summary of a news article using Facebook BART model.
- Generate a summary of a selected news article using the Pegasus model.
- Display the sentiment conveyed in the article.
- Additional:
- Display the word cloud of the summarized article.
- Get wiki info of any personality.

## Installation
To run the app locally, follow these steps:
1. Clone this repository to your local machine.
2. Run the notebook in google colab enivironment.

## Usage
- Select a topic from the sidebar to fetch news articles.
- Click on a news article title to view its summary.
- Enter the URL of a news article to generate a summary.

## Dependencies
- Streamlit: Web application framework for building interactive apps
- Newspaper3k: Library for article scraping and parsing
- Hugging Face Transformers: Library for natural language processing tasks, including summarization
- Requests: Library for making HTTP requests

## Credits
- [Streamlit](https://www.streamlit.io/)
- [Newspaper3k](https://newspaper.readthedocs.io/en/latest/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Requests](https://docs.python-requests.org/en/master/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
