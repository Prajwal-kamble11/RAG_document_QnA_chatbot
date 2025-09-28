  # RAG Document QnA Chatbot
  
  A **Streamlit-based Retrieval-Augmented Generation (RAG) chatbot** that allows you to query PDF documents.  
  It leverages **LangChain**, **Hugging Face embeddings**, and **FAISS** for document retrieval and **Groq LLM** for answering questions.
  
  ---
  
  ## Features
  
  - Load and process PDF documents from a folder (`research_papers`)
  - Split documents into chunks for better retrieval
  - Generate embeddings using Hugging Face models
  - Store and search embeddings efficiently using FAISS
  - Query documents via a simple Streamlit interface
  - Display answers along with relevant document context
  
  ---
  
  ## Installation
  
  1. **Clone the repository**
  
  ```bash

  git clone https://github.com/Prajwal-kamble11/RAG_document_QnA_chatbot.git
  cd RAG_document_QnA_chatbot

  ```
  
  2. Create a virtual environment
     
  ```bash

  python -m venv venv

  ```
  
  3. Activate the virtual environment
  
  -Windows:
  
  ```bash

     venv\Scripts\activate
     
  ```
  
  -Mac/Linux:
  
  ```bash

    source venv/bin/activate

```
  
  4. Install dependencies
  

     ```bash
     
     pip install -r requirements.txt

     ```
  
  ## Setup
  
  1. Create a ```.env``` file in the project root with your API keys:
  
  ```bash

    GROQ_API_KEY=<your_groq_api_key>

  ```
  2. Place your PDF files in the research_papers folder.
  
  
  ## Usage
  
  Run the Streamlit app:
  
  ```bash

    streamlit run app.py

  ```
  
  - Enter a query in the input box to ask questions about your documents.
  
  - Click Document Embedding to build the vector database if it’s the first run.
  
  - View the answer and the relevant document excerpts.
  
  
  
  
  
  
