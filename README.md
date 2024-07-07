# Taylor Swift NLP Chatbot

## Introduction
This project implements a chatbot and knowledge base focused on Taylor Swift using web crawling and natural language processing (NLP) techniques. The chatbot engages users in conversation, providing information about Taylor Swift based on a custom-built knowledge base.

## Features
- Web crawler to extract information from Wikipedia pages about Taylor Swift
- Text preprocessing and important term extraction using TF-IDF
- Knowledge base construction and storage
- Chatbot with natural language understanding capabilities
- Personalized responses based on user interests and dislikes
- Web lookup for queries not found in the knowledge base

## Methodology

### Web Crawler
1. Web crawling using BeautifulSoup and requests
2. Text extraction from Wikipedia pages
3. Text preprocessing (lowercase conversion, non-alphanumeric character removal, stop word removal, tokenization)
4. Important term extraction using TF-IDF
5. Knowledge base construction and storage using pickle

### Chatbot
- Utilizes NLP techniques such as tokenization, stop word removal, cosine similarity, and TF-IDF vectorization
- Dialog management for greetings, farewells, and conversation flow
- Knowledge base retrieval and web lookup for answering queries

## Usage

1. **Web Crawler**: 
   - Run the web crawler script to collect and store Wikipedia articles about Taylor Swift.
2. **Text Processing**: 
   - Execute the text processing script to clean and pre-process the extracted text.
3. **Knowledge Base**: 
   - Build the knowledge base using the processed text and store it for chatbot integration.
4. **Chatbot Interaction**: 
   - Run the chatbot script to start interacting with users and provide information based on the knowledge base.

## Evaluation
The chatbot was evaluated based on ease of use, accuracy of responses, and overall user satisfaction. Survey results showed high scores for ease of use and overall satisfaction, with room for improvement in response accuracy.

## Future Improvements
- Enhance accuracy of responses
- Improve ability to rephrase answers according to user input
- Add support for handling ambiguous queries and subjective opinions

  ## Repository Contents

* `notebooks/`: Jupyter notebooks for web crawling and chatbot implementation
  - `webcrawl.ipynb`: Web scraping and text processing
  - `chatbot.ipynb`: Chatbot implementation and interaction

* `data/`: Contains all data files used and generated by the project
  - `scraped_text/`: Raw text files scraped from Wikipedia
  - `cleaned_text/`: Processed and cleaned text files
  - `knowledge_base.pkl`: Pickle file containing the constructed knowledge base
  - `urls.txt`: List of URLs used for web crawling

* `Report.pdf`: Comprehensive final project report
  
* `NLP Group Project.ppt`: PowerPoint presentation of project findings

* `README.md`: Overview and instructions for the project
