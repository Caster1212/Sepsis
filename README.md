Project: Reducing Diagnostic Errors with a Knowledge Graph and LLMs
Overview
This project aims to reduce diagnostic errors by leveraging a knowledge graph of medical information, specifically focusing on sepsis. The system utilizes Neo4j for storing the knowledge graph and LangChain for embedding the relationships between nodes, enabling retrieval for use in a medical assistant that supports doctors in diagnosis.

The assistant helps doctors by providing guidance on additional patient questions, recommending relevant tests, considering differential diagnoses, and suggesting follow-up steps.

Key Components
Neo4j Knowledge Graph:

A Neo4j database stores relationships and properties related to sepsis, which can be extracted and embedded for use with the language model.
LangChain:

LangChain facilitates embeddings and retrieval from the knowledge graph.
A ChatGPT model is integrated for answering diagnostic-related queries, aimed at assisting doctors in avoiding misdiagnoses.
OpenAI GPT-3.5:

OpenAI's GPT-3.5-turbo model provides natural language processing to analyze patient data and provide diagnostic recommendations.
Chroma:

A vector store is used to store embeddings for efficient retrieval during diagnostic queries.
