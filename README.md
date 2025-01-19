#Competitive Programming Problem Analysis

This repository contains the implementation of **Assignment** by **GDG** (Google Developer Groups), which focuses on implemanting a **Chatbot** by extracting, analyzing, and processing solutions for competitive programming problems from a given PDF. It uses modern tools like **LangChain**, **vector stores**, and **large language models (LLMs)** for intelligent retrieval and question-answering.

---

## Features

- **PDF Text Extraction**: 
  - Extract text from the provided PDF document using efficient text processing libraries.

- **Data Preprocessing**:
  - Split extracted text into smaller, manageable chunks for further analysis.

- **Embedding and Vector Storage**:
  - Generate embeddings using state-of-the-art models like `all-MiniLM-L6-v2`.
  - Store embeddings in a vector store for efficient similarity-based retrieval.

- **Question-Answering System**:
  - Retrieve relevant solutions or contexts from the PDF.
  - Use a language model (e.g., GPT, Ollama, or another LLM) to provide detailed answers.

- **Prompts for Solution Extraction**:
  - Tailor prompts to guide the LLM in providing step-by-step explanations, pseudocode, and complexity analysis.

---

## Prerequisites

### Libraries and Tools
- **Python 3.8+**
- **LangChain**
- **SentenceTransformers**
- **ChromaDB** or **Pinecone**
- **PyPDF2** or **pdfminer**

### Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/your-username/assignment2-gdg.git
cd assignment2-gdg
pip install -r requirements.txt
