# Guide-to-LangChain
This will be a beginner friendly to end to end LangChain guide. 

## 1 Open AI
- Getting Started Notebook has code to load a LLM model from Langchain followed by creating a LL chain with prompt and output parser
- Simple App notebook has the code for an end to end Simple RAG implemented using Langchain
    - Data Ingestion
    - Data Splitter
    - Create Embedding
    - Store in Vector DB
    - Query using retriever

## 2 Ollama
- Created a simple QA system using Ollama package. Download llama3.1 model locally and then run the streamlit app

## 3.1 Data Ingestion
- Created document loader for different document types like text, pdf, website, arxiv, wikipedia. 

## 3.2 Data Transformer
- Notebooks to know understand different text spliter. 
    - Recursive Character Text Splitter
    - Character Text Splitter
    - HTML Text Splitter
    - Recursive Json Splitter

## 4 Embeddings
- Notebook where embeddings are created for the splitted text
    - OpenAI embedding
    - Ollama embedding (Local Llama 3.1)
    - Hugging Face embedding

## 5 Vector Store
- Notebook with code for vector store creation and retriever. 
    - FAISS Vector store
    - Chroma Vector store


### Credit:
Complete Gen AI course by Krish Naik. 
