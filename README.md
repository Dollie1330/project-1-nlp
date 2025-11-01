# University FAQ Chatbot

## Project Overview

This project is a simple FAQ chatbot designed to answer common university-related queries such as admissions, fees, hostel procedures, exam schedules, refund policies, and contacting the university helpdesk. The chatbot uses Natural Language Processing techniques for matching user questions to the most relevant answers stored in its database.

## Workflow Steps

- The FAQ dataset is created directly within the code as a Python DataFrame—no file upload required.
- Text preprocessing (tokenization, lemmatization, stopword removal) is performed using the spaCy library.
- Questions are vectorized using the TF-IDF technique, allowing efficient matching.
- User queries are processed and compared to all stored questions using cosine similarity, returning the best-matching answer.
- A simple interactive loop lets users type questions and receive answers instantly.

## How to Use

1. Open the Colab notebook and execute all cells in order.
2. Enter any university-related question in the provided input prompt.
3. The chatbot will reply with the closest answer from its FAQ database.
4. Type "exit" to end the session.

## Libraries Used

- pandas
- scikit-learn
- spaCy

## Customization and Extensions

- Add more question-answer pairs to the FAQ DataFrame for wider coverage.
- Deploy the logic in web applications (such as Streamlit or Flask) for a richer user interface.
- Integrate more advanced NLP methods for improved semantic matching.
- Connect the chatbot to external CSV, Google Sheets, or databases for scalable FAQs.

