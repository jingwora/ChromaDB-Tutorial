# ChromaDB-Complete-Tutorial

## Introduction
This tutorial will provide you with an introduction to ChromaDB, covering its fundamental and intermediate usage. We will explore topics such as constructing a ChromaDB, generating vectors, performing retrieval, updates, and deletions, as well as techniques for saving and loading data. Additionally, we will delve into a practical application of ChromaDB within a real-world project.

Notebooks: [English](https://github.com/jingwora/ChromaDB-Tutorial/blob/main/01_ChromaDB_Complete_Tutorial-en.ipynb) | [Japanses](https://github.com/jingwora/ChromaDB-Tutorial/blob/main/01_ChromaDB_Complete_Tutorial-ja.ipynb)

## Contents:
- ChromaDB Overview
  - What is ChromaDB?
  - Why ChromaDB
  - Language Support
  - Environment setting
  - Dataset
  - Embeddings
- ChromaDB functions
- Methods on Client
  - EphemeralClient
  - create_collection
  - heartbeat
  - reset
  - get_collection
  - get_or_create_collection
  - list_collections
  - delete_collection
- Methods on Collection
  - add
  - peek
  - count
  - modify
  - get
  - query
  - delete
  - update
  - upsert
- embedding
  - DefaultEmbeddingFunction
  - SentenceTransformerEmbeddingFunction
  - OpenAI

References:
- Chroma docs: https://docs.trychroma.com/
- api-reference: https://docs.trychroma.com/api-reference
- datasets: https://huggingface.co/datasets/jingwora/unstructured-data-multilingual
