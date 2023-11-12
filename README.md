# custom-chatbot
Custom Chatbot using (RAG) Retrieval-augmented generation, Pinecone and Langchain.

Given the private files, 
- You can ask questions on those files
- sentence-transformers/all-MiniLM-L6-v2 will go and perform similarity search and  find relevant chunks of data stored in Pinecone vector store
- Question, relevant chunks of data will then be passed to llm (OpenAI) as a prompt using Langchain
- llm (OpenAI Model) will give a response
- That response will be displayed on screen using streamlit.
