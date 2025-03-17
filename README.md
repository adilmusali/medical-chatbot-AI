# **Medical Chatbot with Generative AI**  

## **Overview**  
This project is an **AI-powered medical chatbot** that leverages **Google Gemini model, LangChain, and Pinecone** for intelligent question-answering and medical information retrieval.  

---

## **🚀 Getting Started**  

### **Prerequisites**  
- **Python 3.10** or later  
- **Conda (Anaconda/Miniconda)**  
- **Pinecone & Google API key**  

### **🔧 Installation Guide**  

#### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/
cd your-repo
```

#### **Step 2: Set Up a Virtual Environment**  
```bash
conda create -n medibot python=3.10 -y
conda activate medibot
```

#### **Step 3: Install Dependencies**  
```bash
pip install -r requirements.txt
```

#### **Step 4: Configure API Keys**  
Create a `.env` file in the root directory and add your **Pinecone & Google API credentials**:  

```
PINECONE_API_KEY="your_pinecone_api_key"
GOOGLE_API_KEY="your_google_api_key"
```

#### **Step 5: Store Embeddings in Pinecone**  
```bash
python store_index.py
```

#### **Step 6: Run the Application**  
```bash
python app.py
```

#### **Step 7: Access the Chatbot**  
Open your browser and navigate to:  
🔗 **http://localhost:8080/**  

---

## **🛠️ Tech Stack**  
- **Python** – Backend logic  
- **LangChain** – LLM orchestration  
- **Flask** – Web framework  
- **Gemini** – Generative AI model  
- **Pinecone** – Vector database for efficient search  

---

## **📌 Features**  
✔️ Medical chatbot powered by **Generative AI**  
✔️ **Semantic search** with **Pinecone embeddings**  
✔️ **Context-aware** responses using **LangChain**  
✔️ **Flask-based UI** for easy interaction  
