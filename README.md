# RAG vs. CAG Differentiation  

This repository provides a comparative analysis of **Retrieval-Augmented Generation (RAG)** and **Context-Augmented Generation (CAG)**. The included Jupyter notebooks explore the differences, strengths, and use cases of these approaches in language model applications.  

## 📂 Repository Structure  

- **`assets/lilianweng_agent.txt`** – text file as context source
- **`rag.ipynb`** – Notebook analyzing the RAG approach, its workflow, and performance. 
- **`cag.ipynb`** – Notebook detailing the CAG approach, how it differs from RAG, and its applications.  
- **`requirements.txt`** – Dependencies required to run the notebooks.  

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```bash
git https://github.com/mohamedlotfy50/rag_vs_cag.git
cd rag_vs_cag
```

### 2️⃣ Install Dependencies  
Ensure you have Python installed (preferably version 3.8+). Then, install the required packages:  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebooks  
Launch Jupyter Notebook and open `rag.ipynb` or `cag.ipynb`:  
```bash
jupyter notebook
```

## 📖 About RAG & CAG  

- **Retrieval-Augmented Generation (RAG)**: Uses external document retrieval to enhance response generation by providing relevant context to a language model.  
- **Context-Augmented Generation (CAG)**: Augments generation by pre-conditioning the model on a structured context rather than external retrieval.  

### 📚 Context Source  
The context used in this project is based on the insights from [Lilian Weng's blog](https://lilianweng.github.io/posts/2023-06-23-agent/), which is an excellent resource on AI agents and related concepts.  
