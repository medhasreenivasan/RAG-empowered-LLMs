# RAG-empowered-LLMs
This repository contains the codebase for a chatbot powered by the RAG (Retrieval-Augmented Generation) process and integrated with ChromaDB for efficient document storage and retrieval.


### Setting up the ChromaDB
If you wish to set up the chromadb server locally follow the below steps
1. To start the chromadb server run the below command: \n
`chroma run --path <path to your DB>` \n
2. To add, delete or create a new collection use the manage_collection.py script \n
`python manage_collection.py NEW <collection_name> <file_path>` \n

If you wish to use chromadb on colab/local with a persist directory follow the below steps:
1. run the script RAG/manage_collection.py to add, delete or create a new collection
2. Use a persistent client to access the data `chromadb.PersistentClient(path=<path to DB>)`
