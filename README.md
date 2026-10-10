
#  RAG & Generative AI Projects

A collection of Python and Google Colab projects focused on Generative AI, Retrieval-Augmented Generation (RAG), LLM-powered data analytics, sentiment analysis, web scraping, and knowledge-oriented document exploration.

##  Projects Overview

This repository contains two projects:

1. **RAG Chatbot** — Document-based question answering using Retrieval-Augmented Generation.
2. **GenAI Analytics and Knowledge Graph** — Exploring datasets and articles using LLMs, sentiment analysis, topic extraction, named entity recognition, and document indexing.

---

##  Project 1: RAG Chatbot

### Overview

The RAG Chatbot project explores how Large Language Models (LLMs) can answer questions using information retrieved from external documents or knowledge sources.

Retrieval-Augmented Generation combines information retrieval with language generation to provide responses based on relevant contextual information.

### Key Concepts

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Document-based question answering
- Semantic search and information retrieval
- Embeddings and vector indexing, where implemented
- Context-aware AI responses

### General Workflow

1. Load the source documents.
2. Process and split documents into smaller chunks.
3. Generate embeddings, if supported by the implementation.
4. Retrieve relevant information for a user query.
5. Provide the retrieved context to an LLM.
6. Generate an answer using the available context.

### Applications

- Document question answering
- Research assistance
- Knowledge retrieval
- AI-powered learning assistants

---

##  Project 2: GenAI Analytics and Knowledge Graph

**Notebook:** `GENAI_analytic_and_knoweldge_graph.ipynb`

### Overview

This project explores Generative AI, natural language processing, traditional machine learning, and document analysis using Python and Google Colab.

It combines LLM-powered data analysis with sentiment classification, web scraping, topic extraction, named entity extraction, and document indexing.

### Key Features

#### 1. LLM-Powered Data Analytics
- Analyze datasets using Pandas.
- Explore natural-language queries with an LLM-powered Pandas agent.
- Compare sentiment predictions with existing labels.

#### 2. IMDb Sentiment Analysis
- Load the IMDb movie review dataset.
- Explore review data and sentiment labels.
- Convert text into TF-IDF features.
- Train a Multinomial Naive Bayes classifier.
- Evaluate predictions using accuracy and classification metrics.

#### 3. Web Scraping
- Fetch web pages using Python Requests.
- Extract article content using BeautifulSoup.
- Prepare text data for further analysis.

#### 4. Topic Extraction
- Identify important topics from article content.
- Explore common themes across multiple documents.
- Use LLMs to summarize and analyze textual information.

#### 5. Named Entity Extraction
Extract entities such as:
- People
- Organizations
- Locations
- Products
- Dates

#### 6. Document Indexing and Retrieval
- Load documents from a local directory.
- Create a document index using LlamaIndex.
- Persist and reload the index.
- Query indexed documents to identify important topics.

**Note:** The current notebook demonstrates topic/entity extraction and vector-based document indexing. A complete knowledge graph with explicit entities, relationships, and graph queries can be added as a future enhancement.

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- LangChain
- OpenAI API
- LlamaIndex
- TF-IDF
- Multinomial Naive Bayes
- Requests
- BeautifulSoup
- Natural Language Processing (NLP)

The exact dependencies may vary between notebooks.

---

##  How to Run

### Option 1: Google Colab

1. Open the notebook from this GitHub repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Open notebook → GitHub**.
4. Search for this repository or paste its URL.
5. Select the required `.ipynb` notebook.
6. Run the cells in order.

### Option 2: Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/SINGHSHEKHAWAT1651786/RAG_GENAI_Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd RAG_GENAI_Project
   ```

3. Install the dependencies required by the selected notebook.

4. Open Jupyter Notebook or JupyterLab and run the notebook cells.

Some notebooks may require Google Colab, additional datasets, or API credentials.

---

##  API Key Security

Some workflows may require an API key.

- Store API keys in environment variables or Google Colab Secrets.
- Never upload API keys, passwords, or private credentials to GitHub.
- Review notebook outputs before committing files.

---

##  Learning Objectives

Through these projects, the repository explores:

- Generative AI fundamentals
- LLM integration with Python
- Retrieval-Augmented Generation
- Data analysis using Pandas
- Text preprocessing and sentiment classification
- Natural language processing
- Web scraping and text extraction
- Topic and entity extraction
- Vector-based document indexing

---

##  Future Improvements

- Improve RAG retrieval quality and document chunking.
- Add source citations to generated answers.
- Compare LLM sentiment analysis with traditional ML models.
- Build an interactive chatbot interface.
- Implement a true knowledge graph with entities and relationships.
- Integrate Neo4j or NetworkX for graph storage and querying.
- Add evaluation datasets and reproducible performance metrics.
- Improve error handling and dependency management.

---

##  Author

**Govind Singh Shekhawat**


---

##  License

A license has not yet been specified. Add a LICENSE file if you intend to define permissions for using, modifying, or distributing this project.

