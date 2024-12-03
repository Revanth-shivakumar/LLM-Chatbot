# Document Processing and Querying with Local LLM

## Overview

This project processes input PDF documents, splits them into pages, and converts the words on each page into embeddings. These embeddings are then stored in a vector database for efficient retrieval. Users can query the document, and a vector search is performed to find the most relevant parts of the document. The relevant information is then passed to a local Large Language Model (LLM) to generate and render the answer.

## Features

- **PDF Document Processing**: Splits input PDF into pages and extracts words.
- **Word Embeddings**: Converts words to embeddings using pre-trained models (e.g., BERT or Sentence-BERT).
- **Vector Database**: Stores embeddings in a vector database (e.g., FAISS) for efficient similarity searches.
- **Vector Search**: Allows querying the database with vector-based similarity search.
- **Answer Generation**: A local LLM is used to generate human-readable answers from the retrieved data.
