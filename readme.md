# Wikipedia Semantic Search with Weaviate and Cohere

## Overview
This project builds a semantic search system using **Weaviate** for vector storage and search, and **Cohere** for generating text embeddings. The system indexes Wikipedia articles, allowing users to perform natural language queries and retrieve the most relevant articles based on their semantic meaning.

---


## Features
- **Custom Embeddings**: Generates embeddings for articles using Cohere's `embed-english-v2.0` model.
- **Semantic Search**: Finds the most relevant articles to a query using vector similarity.



## Requirements
- Python 3.7+
- Weaviate running locally or hosted (e.g., Weaviate Cloud).
- Cohere API key for embedding generation.


### Python Libraries
Install required libraries using:
```bash
pip install -r requirements.txt


### SetUp

1. Start Weaviate
Ensure Weaviate is running. You can use Docker:


2. Download the Wikipedia dataset:

import pandas as pd
wiki_articles = pd.read_pickle('wikipedia.pkl')


Acknowledgments
Weaviate: For vector storage and search capabilities.
Cohere: For providing powerful embedding models.
Wikipedia for the dataset.
Icog Labs for the learning opportunity.
