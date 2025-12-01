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
- **Frameworks/Libraries**: Transformers, ChromaDB, PDFPlumber, LlamaIndex, DiskCache
- **APIs/Models**: OpenAI GPT-4 / GPT-4o / GPT-4o-mini, Google Gemini models, or any other state-of-the-art LLMs
- **Tools used**: Jupyter Notebook for experimentation, development, and workflow execution

---

## 🚀 Getting Started

### Prerequisites
Before you begin, make sure the following are installed on your system:
- Python 3.8+ – Required to run the core application and notebooks.
- Docker (optional) - Useful if you prefer containerized deployment or want to standardize your environment across machines.

### Installation
1. Clone the repo:
git clone (https://github.com/nishu-qatech/Semantic_Spotter_Project)

2. Navigate to the project directory:
cd Semantic_Spotter_Project

3. Install the required dependencies:
pip install -r requirements.txt

- Please note:
  OpenAI API keys are required for the project to function.
  You can generate one from the OpenAI website and update it in the notebook or environment variables.
  We have updated the code and added more models to make it more dynamic in V2 of the project.

4. Run the project notebook
Open Jupyter Notebook and launch:
"Semantic_spotter_Llamaindex_Nishu_Kumari.ipynb"
---

## 📖 Documentation
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information:
- [ChromaDB](https://docs.trychroma.com/)
- [PDFplumber](https://pypi.org/project/pdfplumber/0.1.2/)
- [Sentence Transformes](https://www.sbert.net/docs/)
- [OpenAI](https://platform.openai.com/docs/)
- [Llama-Index](https://www.llamaindex.ai/)

---

## 🛠️ Challenges/Solution

- Issue #1 – Redundant Re-Embedding
- ChromaDB was repeatedly embedding the same data, leading to unnecessary load and slower retrieval.
  **Fix**: Introduced a cache layer to prevent redundant embeddings, reducing overhead and improving retrieval efficiency.

- Issue #2 – Low Relevance in Retrieved Passages
- Some retrieved chunks weren’t the best candidates for answering user queries.
- **Fix**: Implemented a Cross-Encoder–based reranker to refine passage selection, significantly boosting the quality and relevance of responses.

- Issue #3 – Ensuring Answer Accuracy
- Validating the correctness of model-generated answers proved challenging.
- **Fix**: Used GPT-4 as a verification layer to evaluate responses for accuracy and relevance. Added an optional human feedback loop to further strengthen answer validation and improve overall reliability.

---

## 🌟 Future Improvements
- [ ] Expand support for additional GPT-style models (Gemini, Claude, Hugging Face models, etc.)
- [ ] Introduce new advanced features to enhance usability and retrieval quality
- [ ] Add support for additional vector stores such as Pinecone, Weaviate, and others for greater flexibility

---

## 📄License
- This project is distributed under the MIT License.
- For more details, please refer to the LICENSE file.
  
---

## 💬 Contact
For any queries or feedback, feel free to reach out:

- **Email**: nishusrivastava126@gmail.com
- **GitHub**: 

---


```python

```
