# DSA Search Engine: DSmate

The **DSmate** is a Flask-based search engine that enables users to efficiently find relevant coding questions from LeetCode using user-defined keywords. The search engine processes a dataset of 1,900 LeetCode questions, utilizing the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm for ranking the results based on relevance.

## Live Demo
Check out the live version of the website here: [DSmate website](https://dsmate-com.onrender.com/)

## Features
- **Efficient Query Processing**: Uses TF-IDF to calculate the relevance of documents based on user queries.
- **Comprehensive Dataset**: Scraped 1,900 LeetCode questions for users to search through.
- **Inverted Index**: Optimized search speed and accuracy by leveraging an inverted index.
- **User-Friendly Interface**: Built with Flask to provide an intuitive web interface for easy query input and result display.

## Technologies Used
- **Scraping**: Selenium and BeautifulSoup for extracting questions.
- **Search Algorithm**: TF-IDF for ranking search results based on relevance.
- **Web Framework**: Flask for creating the web application.
- **Frontend**: HTML and WTForms for form-based user input.
- **Python**: The core programming language for backend development.
