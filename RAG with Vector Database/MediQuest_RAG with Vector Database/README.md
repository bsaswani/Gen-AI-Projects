# 💊 MediQuest – RAG with Vector Database

# 📌 Overview 

MediQuest is a Retrieval-Augmented Generation (RAG) system that combines the **LLaMA 3.2 – 1B** model with a **FAISS vector database** for intelligent medical question answering.
The system retrieves relevant PubMed abstracts and generates grounded, context-aware responses powered by embeddings and retrieval pipelines.

# ⚙️ Workflow 

1️⃣ Load and preprocess the **PubMedQA** dataset (first 500 samples).  
2️⃣ Split and embed text using **BAAI/bge-small-en-v1.5** embeddings.  
3️⃣ Store embeddings in a **FAISS vector index** for similarity-based retrieval.  
4️⃣ Load the **LLaMA 3.2 – 1B** model via Hugging Face Transformers.  
5️⃣ Define the **RAG chain** combining retriever, context formatter, and response generator.  
6️⃣ Query the system with medical questions to obtain factual, grounded answers.  

# 📊 Dataset  

- **Source**: Hugging Face – PubMedQA (`pqa_labeled`)  
- **Format**: Question, Context, and Answer pairs  
- **Subset Used**: 500 records for efficient retrieval  

# 🛠 Technologies Used  

- Python  
- Hugging Face Transformers (**LLaMA 3.2 – 1B**)  
- LangChain  
- FAISS Vector Database  
- Google Colab  
- Pandas, NumPy, Torch  

# 🚀 Usage  

1️⃣ Open `MediQuest_RAG_with_Vector_Database.ipynb` in **Google Colab**.  
2️⃣ Enter your **Hugging Face token** when prompted.  
3️⃣ Run all cells to initialize embeddings, build the FAISS index, and start querying the RAG system.
