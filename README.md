# SeacareAI
This is AI chatbot for seafarers using Qwen 2.5

## Features

- AI chatbot for seafarers
- Uses Qwen2.5-0.5B-Instruct
- Retrieval-Augmented Generation (RAG)
- FAISS vector database
- Sentence Transformers for document embeddings
- Gradio web interface
- Answers based on maritime reference documents
- Keyword specific

- ## Technologies Used

- Python
- Transformers (Hugging Face)
- Qwen2.5-0.5B-Instruct
- Sentence Transformers
- FAISS
- LangChain
- Pandas
- Gradio
- 
 - ##Dataset
- Maritime reference PDF documents used as the knowledge base.
- Save the PDF files to the local environment
- Change the File location in the code

- ## How It Works

1. Load the Qwen2.5 language model.
2. Read maritime PDF documents.
3. Split documents into smaller text chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Retrieve the most relevant document chunks for the user's question.
7. Combine the retrieved context with the user's query.
8. Generate a final response using Qwen2.5.
9. Display the answer through a Gradio interface.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/SeacareAI.git
```

Navigate to the project folder:

```bash
cd SeacareAI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook or application.

---

## Author

Sachini Dushyanthi

- 
