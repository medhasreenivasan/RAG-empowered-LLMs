# RAG-empowered-LLMs
This repository contains the codebase for a chatbot powered by the RAG (Retrieval-Augmented Generation) process and integrated with ChromaDB for efficient document storage and retrieval.


# Setting up the ChromaDB server
To start the chromadb server run the below command:
`chroma run --path <path to your DB>`
To add, delete or create new collection use the manage_collection.py script
`python manage_collection.py NEW <collection_name> <file_path>`
