# AccuKnox AI/ML Trainee Assignment

This repository contains my submission for the **AccuKnox AI/ML Trainee Assignment**. The work demonstrates practical implementation of REST APIs, Python, SQLite, data processing, visualization, and basic AI/ML concepts.

## Assignment 1 — Python, APIs and Database

The first part focuses on working with external APIs and storing the retrieved data in a local SQLite database. Book information was retrieved from the **Open Library API**, processed to extract the title, author, and publication year, and then stored and verified using SQLite.

The second task involved retrieving student test scores through a REST API. The data was processed using Pandas, valid scores were selected, and the average mathematics score was calculated. A bar chart was also created to visualize the student scores and saved as `student_scores.png`.

The third task demonstrates importing user information from a CSV file into SQLite. The CSV data was read using Pandas and inserted into a SQLite table with basic duplicate protection.

Key technologies used in Assignment 1 include:

* Python and Requests for API communication
* Pandas and Matplotlib for data processing and visualization
* SQLite for local database storage
* Google Colab for development and execution

## Assignment 2 — AI/ML Concepts

The second part covers fundamental AI/ML concepts, including a self-assessment of knowledge in LLMs, Deep Learning, AI, and Machine Learning.

It also explains the high-level architecture of an **LLM-based chatbot**, including the user interface, backend, conversation context, knowledge retrieval, prompt construction, LLM, and response handling. The role of **Retrieval-Augmented Generation (RAG)** is also discussed for applications that need information from external or private documents.

The final section explains **vector databases**, embeddings, semantic similarity search, and their use in RAG applications. For the given hypothetical internal company chatbot, **Qdrant** was selected because of its vector search capabilities, metadata filtering, self-hosting support, and suitability for Python-based AI applications.

**Assignment 2:** [View Assignment 2 on Google Drive](https://drive.google.com/file/d/1YdlRTfXQPiwZwh_yuYdK-ogUAqNo9R2u/view?usp=sharing)

## Repository Contents

The main files included in this repository are:

* `AccuKnox_AI_ML_Trainee_Assignment.ipynb` — complete implementation and assignment responses
* `assignment.db` — SQLite database containing the processed data
* `users.csv` — sample CSV data used for database import
* `student_scores.png` — visualization of student mathematics scores

## Author

**Tanuja Mahesh Modak**
B.Tech. in Data Science
