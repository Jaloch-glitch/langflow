# langflow


# Test Langflow

In this repo, there is an instantiate of langflow for playing with it.

For this usecase, we build a RAG that reads our pdf document.

# General Workflow
Start
 ↓
Ingest PDF Document
 ↓
Split Document
 ↓
Embed Text Chunks (Create Vectors)
 ↓
Store Embeddings in Vector Database
 ↓
Create Retriever
 ↓
End

# Usage
Usage
To use, first clone the repo, then:

Ensure you have python 3.10

pyenv install 3.10.11
pyenv global 3.10.11
Install the requirements:

pip install poetry 
poetry config virtualenvs.in-project true
poetry install --no-root
poetry shell
Run langflow:

to inialise the project
langflow run
