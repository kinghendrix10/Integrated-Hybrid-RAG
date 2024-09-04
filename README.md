# Hybrid RAG Repository

## Introduction

This repository contains code and resources for a hybrid retrieval-augmented generation (RAG) system. The system integrates various components to load data into Neo4j and Qdrant, query legislative documents, and generate responses using large language models (LLMs). The primary goal of this repository is to provide a comprehensive solution for analyzing and querying legislative documents.

## Installation

To set up the environment and install the necessary dependencies, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/kinghendrix10/hybrid-RAG.git
   cd hybrid-RAG
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up Google Drive for data storage:
   - Mount Google Drive in your Jupyter notebook:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

## Usage

To run the Jupyter notebooks and utilize the functionality provided by this repository, follow these steps:

1. Open the Jupyter notebook `Can_Policy_DataStore_Loader.ipynb`:
   - This notebook includes code for installing dependencies, setting up logging, and mounting Google Drive.
   - It implements functionality for loading data into Neo4j and Qdrant.

2. Open the Jupyter notebook `Can_Policy_Llama_Index_Hybrid_RAG_v2.ipynb`:
   - This notebook includes code for querying legislative documents and generating responses using LLMs.
   - It provides an interactive interface for querying the knowledge base.

## Contributing

We welcome contributions to this repository. If you would like to contribute, please follow these guidelines:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and ensure that the code is properly tested.
3. Submit a pull request with a clear description of your changes and the problem they solve.

Thank you for your contributions!
