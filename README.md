# Advanced RAG Pipeline
  
This repository demonstrates a Retrieval-Augmented Generation (RAG) pipeline  
built using LangChain and Ollama integrations.  
  
The project processes the NIPS 2017 paper, "Attention is All You Need",  
by splitting its PDF into manageable chunks, indexing them with a Chroma vector store,  
and retrieving relevant context to generate answers for user queries.  
  
## Key Features
  
- **Document Processing:** Loads and splits the PDF into overlapping chunks.
- **Embeddings & Indexing:** Uses the `deepseek-r1` model for generating embeddings  
  and indexes them with Chroma.
- **Retrieval & Prompting:** Retrieves context and uses prompt chaining to generate answers.
- **Integration:** Built with LangChain and Ollama for seamless model interactions.
  
## Repository Structure
  
- **Pipfile & Pipfile.lock:** Dependency management using Pipenv.
- **NIPS-2017-attention-is-all-you-need-Paper.pdf:** The research paper used as the data source.
- **Pipeline Code:** Implementation of the RAG system.
  
## Prerequisites
  
- Python 3.7 or later
- [Pipenv](https://pipenv.pypa.io/en/latest/)
  
## Getting Started
  
1. Clone the repository:
   ```bash
   git clone https://github.com/harshhmaniya/Advance-RAG-Pipeline.git
   cd Advance-RAG-Pipeline
