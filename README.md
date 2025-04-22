# LangChain Components: Data Ingestion, Transformation, Embeddings, and Vector Databases

Welcome to my LangChain exploration repository! This project dives into the **core components of LangChain**, demonstrating how to work with:

- ✅ Data Ingestion  
- ✅ Text Transformation  
- ✅ Embedding Models  
- ✅ Vector Databases

---

## 📁 Project Structure

langchain/ ├── data_ingestion/ │ ├── text_loader.py │ ├── pdf_loader.py │ └── web_loader.py ├── data_transformation/ │ └── text_splitter.py ├── embeddings/ │ ├── openai_embeddings.py │ └── huggingface_embeddings.py ├── vector_databases/ │ ├── faiss_store.py │ └── chroma_store.py ├── .env └── README.md

yaml
Copy
Edit

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+
- OpenAI API Key (for OpenAI Embeddings)
- Hugging Face API Key (for Hugging Face Models)

### 🔧 Installation

```bash
git clone https://github.com/shivam-kr935/langchain.git
cd langchain
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
🔐 Add Environment Variables
Create a .env file and add:

ini
Copy
Edit
OPENAI_API_KEY=your_openai_key
HUGGINGFACE_API_KEY=your_hf_key
📄 Data Ingestion
Implemented in /data_ingestion
Load documents from:

.txt files – using TextLoader

.pdf files – using PyPDFLoader

Web URLs – using WebBaseLoader

✂️ Text Transformation
Implemented in /data_transformation

Use RecursiveCharacterTextSplitter to chunk text.

Control chunk size and overlap for better embedding context.

🧠 Embeddings
Implemented in /embeddings

OpenAIEmbedding – For GPT-based embedding vectors

HuggingFaceEmbedding – Use local/hosted transformer models

🗃️ Vector Databases
Implemented in /vector_databases

🔍 FAISS – For similarity search

🧠 Chroma – Lightweight, fast embedding storage

Use these to store and retrieve document vectors.

🧪 Running Scripts
You can run each file individually like this:

bash
Copy
Edit
python data_ingestion/text_loader.py
Make sure your files are placed in the appropriate location.

📚 References
LangChain Docs

OpenAI API

Hugging Face

FAISS

Chroma

🤝 Contributions
Feel free to open issues or PRs to improve the repo or add use cases!

📄 License
This project is licensed under the MIT License.

🧠 Built with learning & exploration by Shivam Kumar
📬 Contact: GitHub
