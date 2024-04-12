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
- Overview:
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/9c16217e-ab5d-4188-98de-bf346358598b" alt="Overview" width="800" height="600">- 

- Select a topic from the sidebar to fetch news articles.
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/02e526d8-45bd-4cd3-ad47-e40521b0e8ea" alt="Select a topic" width="300" height="800">

- View summary of various articles under that topic.
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/3aa0bfcc-a52e-4531-b09a-457db175db4e" alt="View summary" width="800" height="600">
  
- Select the amount of time you want to spend on reading a summary.
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/8e1083b7-ff1f-40d7-8406-257bc180d1ec" alt="Select reading time" width="800" height="200">

- Enter the URL of a news article to generate a summary from the Pegasus Model
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/78343a0b-2120-41ad-921b-1c4d986cd7c3" alt="Enter article URL" width="800" height="400">

- Wiki info section
<img src="https://github.com/Ishanoic/News-Summarizer/assets/144539284/c067f6ad-890b-499d-b3e2-8286c7f7b820" alt="Wiki info" width="400" height="300">


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
