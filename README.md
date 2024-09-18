# Hybrid RAG Repository

## Introduction

This repository contains code and resources for a hybrid retrieval-augmented generation (RAG) system. The system integrates various components to load data into Neo4j and Qdrant, query documents, and generate responses using large language models (LLMs). The primary goal of this repository is to provide a comprehensive solution for analyzing and querying documents using a combination of Graph and Vector RAG query engines.

## Usage

To run the Jupyter notebooks and utilize the functionality provided by this repository, follow these steps:

1. Open the Jupyter notebook `Loader.ipynb`:
   - This notebook includes code for installing dependencies, setting up logging, and mounting Google Drive.
   - It implements functionality for loading data into Neo4j and Qdrant.

2. Open the Jupyter notebook `Hybrid_RAG_v2.ipynb`:
   - This notebook includes code for querying Graph and Vector databases and generating responses using LLMs.
   - It provides an interactive interface for querying the knowledge base.
