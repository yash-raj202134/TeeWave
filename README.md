# TeeWave

## Introduction

TeeWave is a T-shirt store management application that leverages LangChain, Streamlit, and Chromadb integration to provide a dynamic and intelligent approach to handling T-shirt store operations. The application utilizes Google's PaLM large language model (LLM) and a MySQL database to perform various queries and tasks related to T-shirt inventory management.

## Features

- **T-shirt Inventory Management:** Query the inventory for different brands, colors, and sizes of T-shirts.
- **Discount Application:** Calculate the revenue generated from selling T-shirts with discounts applied.
- **Semantic Similarity:** Retrieve semantically similar examples using HuggingFace embeddings and Chroma vector store.

## Dependencies

The project requires the following libraries and packages:

- [LangChain](https://github.com/hwchase17/langchain) version 0.0.284
- [Python-dotenv](https://github.com/theskumar/python-dotenv) version 1.0.0
- [Streamlit](https://streamlit.io/) version 1.22.0
- [TikToken](https://github.com/openai/tiktoken) version 0.4.0
- [FAISS CPU](https://github.com/facebookresearch/faiss) version 1.7.4
- [MySQL Connector Python](https://pypi.org/project/mysql-connector-python/) version 8.0.30
- [PyMySQL](https://github.com/PyMySQL/PyMySQL) version 1.0.2
- [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) version 2.2.2
- [ChromaDB](https://www.trychroma.com/) version 0.2.0
- [Google Generative AI](https://developers.google.com/generative-ai) API

You can install these dependencies using the following command:

```bash
pip install -r requirements.txt
```


## Setup
Follow these steps to set up the TeeWave application:

## Clone the repository:
```bash
Copy code
git clone <repository_url>
```
```bash
cd teewave
```
### Create a .env file: In the root directory of the project, create a .env file and add the following variables:
plaintext
Copy code
GOOGLE_API_KEY=your_google_api_key
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=your_db_host
DB_NAME=your_db_name

## Install dependencies:
```bash
pip install -r requirements.txt
```
Set up the MySQL database:
Use the provided SQL schema to create the required tables in your MySQL database.
Make sure the database name, user, and password match the settings in your .env file.
## Modify the app.py file:
Adjust any configuration settings in the app.py file to match your setup.
Usage
Run the application:
```bash
streamlit run app.py
```
## Interact with the application: Use the provided user interface to perform various tasks and queries.
Troubleshooting
Ensure that the Google API key and MySQL database credentials in the .env file are correct and up to date.
Double-check your database connection string and the database schema.
If you encounter any errors, review the application logs for more details on the issue.
Contributions
Contributions are welcome! Please submit a pull request with your changes.

## License
This project is licensed under the MIT License.
