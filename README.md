# Semantic Spotter lamaindex Project
Simplifying insurance document queries with the power of Retrieval-Augmented Generation (RAG) and advanced embeddings with Llama-Index and OpenAI's GPT models.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)

---

## ✨ About the Project
**RAG Insurance Assistant** is designed to make insurance information effortlessly understandable. Instead of wading through policy booklets, claim rules, and dense legal text, users can simply ask questions and receive clear, accurate answers in seconds.

At its core, the solution uses ***Retrieval-Augmented Generation (RAG)** with **LlamaIndex** to pinpoint the most relevant sections from insurance documents. These retrieved insights are then paired with the reasoning and language capabilities of advanced AI models like GPT-4 or Gemini. This two-layer process ensures reliable, context-aware responses—turning complex insurance content into accessible, actionable information.

Key Benefits:
- **Streamlined Information Access**: No more digging through lengthy documents. Ask a question and get clear, accurate answers instantly.
- **Enhanced Contextual Understanding**: Converts dense legal and policy language into simple, user-friendly explanations.
- **Scalable and Robust**: Efficiently processes large volumes of documents, making it suitable for individual users, support teams, and enterprise applications.

Whether you're a policyholder trying to understand your coverage or an insurance professional aiming to enhance customer interactions, the RAG Insurance Assistant reshapes how users engage with insurance information.


Example Use Cases:
- "What is covered under my health insurance policy?"
- "How can I file a claim for vehicle insurance?"

---

## 🔍 Key Features
- 🌟 **Efficient Document Retrieval**: Uses LlamaIndex to surface the most relevant sections of insurance documents with precision, ensuring answers are grounded in the right context.
- 🤖 **Context-Aware Responses**: Blends powerful retrievers with AI models like GPT-4 or Gemini to deliver clear, accurate explanations from dense policy text.
- 🔄 **Vector Store Integration**: Employs ChromaDB for storing and querying embeddings, enabling fast, scalable search even on large datasets.
- 📄 **Document Agnostic**: Supports multiple formats—including PDFs, Word files, and text documents—offering flexibility across insurance materials.
- 🧩 **Customized Chunking Strategies**: Utilizes advanced chunking and overlap techniques to preserve context and boost retrieval quality.
- 🌐 **Deployed Anywhere**: Run it locally for personal use or scale it in the cloud for enterprise workflows—your environment, your choice.
- 🔑 **Secure By Design**: Protects sensitive insurance data with secure API key handling and controlled access.
- 📊 **Analytics-Ready**: Optional analytics integration allows you to track query trends and refine document sets or user experience over time.
- 💬 **Interactive Querying**: Provides a conversational interface that turns policy exploration into a smooth, intuitive dialogue.
- 🚀 **Future-Ready Architecture**: Built with extensibility in mind—easily adaptable for other document-heavy domains such as legal, banking, or healthcare.
---

## 🛠️ Tech Stack
- **Language**: Python (developed and tested in Jupyter Notebook)
- **Frameworks/Libraries**: Transformers, ChromaDB, PDFplumber, Llama-Index, Disk Cache
- **APIs/Models**: OpenAI's GPT-4/ GPT-4o/ GPT-4o-mini or Gemini API or any other State-of-the-Art models
- **Tools used**: Jupyter Notebook

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation
1. Clone the repo:
git clone https://github.com/

2. Navigate to the project directory:
cd Semantic_Spotter_AI_Project_GenAI_UpGrad_IIITB

3. Install the required dependencies:
pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function. You can obtain them from the OpenAI website and change the same in the code. We have updated the code and added more models to make it more dynamic in V2 of the project.

4. Run the main file from Jupyter environment:
"Semantic_spotter_lamaindex_Sandeep.ipynb"

---

## 📖 Documentation
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:
- [ChromaDB](https://docs.trychroma.com/)
- [PDFplumber](https://pypi.org/project/pdfplumber/0.1.2/)
- [Sentence Transformes](https://www.sbert.net/docs/)
- [OpenAI](https://platform.openai.com/docs/)
- [Llama-Index](https://www.llamaindex.ai/)

---

## 🛠️ Challenges/Issues Faced with fixes

- [Issue #1](Cache layer was added in ChromaDB to prevent re-embedding of the data. This was done to avoid overloading the ChromaDB server with data and to make the retrieval process more efficient.)

- [Issue #2](Cross Encoder based Reranker was added to better select the most relevant passages from the document. This was done to improve the quality of the answers to the user queries.)

- [Issue #3](Verifying the correctness of the answers given by the model was a challenge. We used GPT-4 to verify the answers provided by the model since it is a state-of-the-art model. This was done to ensure that the answers provided by the model are accurate and relevant. We also included a human feedback system to verify the correctness of the answers provided by the model. This was done to ensure that the answers provided by the model are accurate and relevant.)

---

## 🌟 Future Improvements
- [ ] Add more selectable GPT models to the project(Gemini, Claude AI, Huggingface models etc).
- [ ] Add more features to the project.
- [ ] Add more selectable Vector Store to the project(Pinecone, Weaviate etc).

---

## 💬 Contact
For any queries or feedback, feel free to reach out:

- **Email**: 
- **GitHub**: 
- **LinkedIn**:

---


```python

```
