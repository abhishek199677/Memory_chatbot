# Memory_chatbot
store into vectordb(FAISS), gpt-model, uri api for real time conversation

Stores the message content in the chat interface.
Generates embeddings for the message using a pre-defined embedding model.
Stores the embeddings in a FAISS vector store for efficient similarity search.
Retrieves relevant past conversations by comparing embeddings, enabling the system to remember previous questions and context.
Uses URIs for chat embeddings to link and retrieve specific conversation segments.
Implements Retrieval-Augmented Generation (RAG) approach to fetch relevant information and generate context-aware responses.
This setup allows the system to remember past interactions and provide more coherent and contextually relevant