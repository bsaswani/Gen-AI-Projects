# 🤖 SmartPrep AI Agent

# 📌 Overview

SmartPrep AI Agent is an interactive interview preparation system powered by LLaMA 3.2 – 1B. It integrates with **LangChain and FAISS** to retrieve job-specific knowledge from a structured PDF containing 20 IT job roles. The agent dynamically generates interview questions, concise answers, and revision topics based on user input (e.g., “Python Developer”).

# ⚙️ Workflow

1️⃣ Load the custom 20-page job role knowledge base PDF.

2️⃣ Convert each page into embeddings using Sentence Transformers.

3️⃣ Store embeddings in a FAISS vector index for similarity-based retrieval.

4️⃣ Load the LLaMA 3.2 – 1B model and define a dynamic prompt for role-specific Q&A generation.

5️⃣ Interact with the console-based agent to receive contextual interview questions and revision topics.

# 📊 Knowledge Base

Source: Custom PDF with 20 IT job roles

Structure: One role per page (skills, core concepts, and sample questions)

Purpose: Context retrieval for dynamic interview preparation

# 🛠 Technologies Used

1. Python

2. Hugging Face Transformers (LLaMA 3.2 – 1B)

3. LangChain

4. FAISS Vector Database

5. Sentence Transformers

6. Google Colab

# 🚀 Usage

1️⃣ Open SmartPrep AI Agent.ipynb in Google Colab.

2️⃣ Upload your 20-role PDF (e.g., SmartPrep_AI_Agent_KnowledgeBase.pdf).

3️⃣ Run all cells to initialize embeddings, FAISS index, and model pipeline.

4️⃣ Enter any job role (e.g., “Data Scientist”, “Java Developer”) to generate interview preparation content.
