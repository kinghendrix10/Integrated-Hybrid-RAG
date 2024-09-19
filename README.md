# Integrated Hybrid RAG

## Introduction

This repository contains code and resources for a hybrid retrieval-augmented generation (RAG) system. The system integrates various components to load data into Neo4j and Qdrant, query legislative documents, and generate responses using large language models (LLMs). The primary goal of this repository is to provide a comprehensive solution for analyzing and querying legislative documents.

## Usage

To run the Jupyter notebooks and utilize the functionality provided by this repository, follow these steps:

1. Open the Jupyter notebook `Can_Policy_DataStore_Loader.ipynb`:
   - This notebook includes code for installing dependencies, setting up logging, and mounting Google Drive.
   - It implements functionality for loading data into Neo4j and Qdrant.

2. Open the Jupyter notebook `Can_Policy_Llama_Index_Hybrid_RAG_v2.ipynb`:
   - This notebook includes code for querying legislative documents and generating responses using LLMs.
   - It provides an interactive interface for querying the knowledge base.
   - Specific functionalities include extracting bill information, creating graph data, and loading data into Neo4j and Qdrant.
   - Outputs include structured data about bills, amendments, key provisions, definitions, persons involved, affected parties, and related acts.

3. Open the Jupyter notebook `CaselawAI/CaseLaw_DataStore_Loader_v3_2 (2).ipynb`:
   - This notebook includes code for loading case law data into Neo4j and Qdrant.
   - It provides functionalities for extracting and structuring case law information.

4. Open the Jupyter notebook `CaselawAI/Llama_Index_Hybrid_RAG_v3 (1).ipynb`:
   - This notebook includes code for querying case law documents and generating responses using LLMs.
   - It provides an interactive interface for querying the case law knowledge base.

## Dependencies

The repository uses the following dependencies and their versions:
- `llama-index`
- `neo4j`
- `llama-index-graph-stores-neo4j`
- `llama-parse`
- `qdrant_client`
- `llama-index-vector-stores-qdrant`
- `llama-index-embeddings-huggingface`
- `llama-index-embeddings-fastembed`
- `llama-index-llms-groq`

## Database Setup

### Neo4j
- Ensure you have a running instance of Neo4j.
- Set the `NEO4J_URL` and `NEO4J_PASSWORD` in your environment variables or in the notebook.

### Qdrant
- Ensure you have a running instance of Qdrant.
- Set the `QDRANT_URL` and `QDRANT_API_KEY` in your environment variables or in the notebook.

## Benefits of Combining Knowledge Graphs and Vector Embedding in RAG

Combining knowledge graphs and vector embedding in a hybrid RAG system offers several benefits:

1. **Enhanced Contextual Understanding**: Knowledge graphs provide structured relationships between entities, while vector embeddings capture semantic similarities. This combination allows for a more comprehensive understanding of the context and relationships within the data.

2. **Improved Retrieval Accuracy**: By leveraging both knowledge graphs and vector embeddings, the system can retrieve more relevant and accurate information. Knowledge graphs help in identifying explicit relationships, while vector embeddings capture implicit connections.

3. **Robust Query Handling**: The hybrid approach enables the system to handle a wide range of queries, from specific entity-based questions to more abstract and semantic queries. This flexibility enhances the system's ability to provide meaningful and accurate responses.

4. **Scalability and Efficiency**: The integration of knowledge graphs and vector embeddings allows for efficient indexing and retrieval of large-scale data. This scalability ensures that the system can handle extensive datasets and provide quick responses.

## Contributing

Contributions to this repo especially regarding performance evaluation!!
