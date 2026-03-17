# 🤖 Generative AI Bootcamp

A **comprehensive, hands-on bootcamp** that takes you from Python fundamentals all the way to building production-ready Generative AI applications. This repository contains structured weekly materials — Jupyter notebooks, datasets, and lecture resources — covering classical NLP, deep learning, transformers, LangChain, RAG, and advanced prompt engineering.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Repository Structure](#repository-structure)
- [Weekly Curriculum](#weekly-curriculum)
  - [Week 1 — Environment Setup & Python Foundations](#week-1--environment-setup--python-foundations)
  - [Week 2 — Classical Machine Learning & NLP](#week-2--classical-machine-learning--nlp)
  - [Week 3 — Deep Learning for NLP](#week-3--deep-learning-for-nlp)
  - [Week 4 — Transformers & Generative AI Foundations](#week-4--transformers--generative-ai-foundations)
  - [Week 5 — Building AI Applications with LangChain](#week-5--building-ai-applications-with-langchain)
  - [Week 6 — Retrieval-Augmented Generation (RAG)](#week-6--retrieval-augmented-generation-rag)
  - [Week 7 — Advanced Prompt Engineering](#week-7--advanced-prompt-engineering)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Technologies & Libraries](#technologies--libraries)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This bootcamp is designed for anyone who wants to understand and build with Generative AI — from the foundational concepts of NLP and neural networks to modern techniques like Retrieval-Augmented Generation (RAG) and prompt engineering. Each week builds on the previous one, progressively increasing in complexity.

**By the end of this bootcamp, you will be able to:**

- Preprocess and engineer features from text data
- Build and train neural networks (Perceptron, RNN, LSTM) for NLP tasks
- Understand the Transformer architecture and attention mechanism
- Work with embeddings from OpenAI, HuggingFace, and Ollama
- Build conversational chatbots and AI-powered search engines using LangChain
- Implement Retrieval-Augmented Generation (RAG) pipelines with vector stores
- Apply advanced prompt engineering techniques for better AI outputs

---

## Prerequisites

- **Python 3.9+** installed on your machine
- Basic understanding of Python programming
- Familiarity with Jupyter Notebooks
- A code editor or IDE (VS Code recommended)
- API keys for the following services (see [Environment Variables](#environment-variables)):
  - [OpenAI](https://platform.openai.com/)
  - [HuggingFace](https://huggingface.co/)
  - [Groq](https://console.groq.com/)
  - [LangChain / LangSmith](https://smith.langchain.com/)

---

## Repository Structure

```
GenerativeAI-Bootcamp/
│
├── week_1/                          # Environment setup & Python basics
│   └── IDE_&_Environment_setup.ipynb
│
├── week_2/                          # Classical ML & NLP
│   ├── Applied_Classical_Machine_Learning_week_4.ipynb
│   ├── Text preprocessing/          # Tokenization, Stemming, Lemmatization, etc.
│   │   ├── text_preprocessing1_tokenization.ipynb
│   │   ├── text_preprocessing2_stemming.ipynb
│   │   ├── text_preprocessing3_lemmatization.ipynb
│   │   ├── text_preprocessing4_stopwords.ipynb
│   │   ├── text_preprocessing5_NER.ipynb
│   │   └── text_preprocessing6_POS.ipynb
│   └── Feature Engineering/         # BOW, N-grams, TF-IDF
│       ├── feature_engineering_bag_of_words_and_ngram.ipynb
│       └── feature_engineering_tfidf.ipynb
│
├── week_3/                          # Deep Learning for NLP
│   ├── perceptron_neural_network/   # Neural network fundamentals & churn modeling
│   ├── recurrent_neural_network/    # Simple RNN & IMDB sentiment analysis
│   └── long_short_term_memory/      # LSTM networks
│
├── week_4/                          # Transformers & Generative AI
│   ├── week_4_Intro_to_Generative_AI_(Transformer_Mechanism).ipynb
│   ├── simple_application_with_LCEL.ipynb
│   └── Embeddings/                  # OpenAI, HuggingFace & Ollama embeddings
│       ├── openai_embedding.ipynb
│       ├── huggingface_embedding.ipynb
│       └── ollama_embedding.ipynb
│
├── week_5/                          # AI Applications with LangChain
│   ├── chatbot.ipynb
│   └── search_engine.ipynb
│
├── week_6/                          # Retrieval-Augmented Generation (RAG)
│   ├── week_6_Retrieval_Augmented_Generation_(RAG).ipynb
│   └── vector_stores_and_retrievers(RAG)_1.ipynb
│
├── week_7/                          # Advanced Prompt Engineering
│   └── prompt_techniques.ipynb
│
├── micellaneous codes/              # Supplementary exercises (file I/O, etc.)
│   └── file_and_exception.ipynb
│
├── lecture_slide_by_week/           # Links to lecture presentations
│   └── week_1_slide_links.ipynb
│
├── capstone_project/                # Final capstone project (coming soon)
│
├── requirements.txt                 # Python dependencies
├── .env                             # API keys (not tracked in git)
└── .gitignore
```

---

## Weekly Curriculum

### Week 1 — Environment Setup & Python Foundations

> **Goal:** Set up your development environment and review Python essentials for AI.

| Notebook | Description |
|----------|-------------|
| `IDE_&_Environment_setup.ipynb` | Install Python, configure your IDE, set up virtual environments, and verify your setup |

**Key Topics:** Python installation, IDE configuration, virtual environments, package management

---

### Week 2 — Classical Machine Learning & NLP

> **Goal:** Learn text preprocessing techniques and feature engineering methods used in traditional NLP.

#### Text Preprocessing

| Notebook | Description |
|----------|-------------|
| `text_preprocessing1_tokenization.ipynb` | Breaking text into tokens (words, sentences, subwords) |
| `text_preprocessing2_stemming.ipynb` | Reducing words to their root form using stemming algorithms |
| `text_preprocessing3_lemmatization.ipynb` | Context-aware word normalization with lemmatization |
| `text_preprocessing4_stopwords.ipynb` | Identifying and removing stopwords |
| `text_preprocessing5_NER.ipynb` | Named Entity Recognition — extracting people, places, organizations |
| `text_preprocessing6_POS.ipynb` | Part-of-Speech tagging for grammatical analysis |

#### Feature Engineering

| Notebook | Description |
|----------|-------------|
| `feature_engineering_bag_of_words_and_ngram.ipynb` | Bag of Words (BOW) and N-gram representations |
| `feature_engineering_tfidf.ipynb` | TF-IDF vectorization for text features |

#### Applied Machine Learning

| Notebook | Description |
|----------|-------------|
| `Applied_Classical_Machine_Learning_week_4.ipynb` | End-to-end ML pipeline with text classification |

**Key Topics:** Tokenization, Stemming, Lemmatization, Stopwords, NER, POS Tagging, BOW, N-grams, TF-IDF, Scikit-learn

---

### Week 3 — Deep Learning for NLP

> **Goal:** Understand and implement neural network architectures for natural language processing.

#### Perceptron & Feed-Forward Neural Networks

| Notebook | Description |
|----------|-------------|
| `week_3_Deep_Learning_for_NLP_(Neural_Network).ipynb` | Deep dive into neural network theory and implementation |
| `churn_modelling.ipynb` | Practical application — predicting customer churn with neural networks |

#### Recurrent Neural Networks (RNN)

| Notebook | Description |
|----------|-------------|
| `week_3_Deep_Learning_for_NLP_(RNN).ipynb` | RNN architecture and theory for sequential data |
| `simple_rnn.ipynb` | Building a simple RNN from scratch |
| `prediction.ipynb` | Using trained RNN models for inference |

#### Long Short-Term Memory (LSTM)

| Notebook | Description |
|----------|-------------|
| `week_3_Deep_Learning_for_NLP_(LSTM).ipynb` | LSTM theory — solving the vanishing gradient problem |
| `lstm.ipynb` | Hands-on LSTM implementation |

**Key Topics:** Perceptrons, Backpropagation, RNN, LSTM, Vanishing Gradients, TensorFlow, TensorBoard

---

### Week 4 — Transformers & Generative AI Foundations

> **Goal:** Understand the Transformer architecture and begin working with LLMs and embeddings.

| Notebook | Description |
|----------|-------------|
| `week_4_Intro_to_Generative_AI_(Transformer_Mechanism).ipynb` | Self-attention, multi-head attention, and Transformer architecture |
| `simple_application_with_LCEL.ipynb` | Building a simple app with LangChain Expression Language (LCEL) |

#### Embeddings

| Notebook | Description |
|----------|-------------|
| `openai_embedding.ipynb` | Generating and using OpenAI text embeddings |
| `huggingface_embedding.ipynb` | Working with HuggingFace sentence-transformers |
| `ollama_embedding.ipynb` | Local embeddings with Ollama |

**Key Topics:** Transformers, Self-Attention, Positional Encoding, Embeddings, LangChain, LCEL

---

### Week 5 — Building AI Applications with LangChain

> **Goal:** Build real-world AI applications — a conversational chatbot and an AI-powered search engine.

| Notebook | Description |
|----------|-------------|
| `chatbot.ipynb` | Build a conversational AI chatbot with memory and context management |
| `search_engine.ipynb` | Create an AI-powered search engine using LangChain tools and agents |

**Key Topics:** LangChain Chains, Agents, Memory, Tools, Conversational AI

---

### Week 6 — Retrieval-Augmented Generation (RAG)

> **Goal:** Build RAG pipelines that ground LLM responses in real data using vector stores and retrievers.

| Notebook | Description |
|----------|-------------|
| `week_6_Retrieval_Augmented_Generation_(RAG).ipynb` | Complete RAG theory and implementation walkthrough |
| `vector_stores_and_retrievers(RAG)_1.ipynb` | Hands-on with Chroma vector stores, document loaders, and retrievers |

**Key Topics:** RAG Architecture, Vector Stores, Chroma, FAISS, Document Loaders, Text Splitters, Retrievers

---

### Week 7 — Advanced Prompt Engineering

> **Goal:** Master prompt engineering techniques to get the best results from LLMs.

| Notebook | Description |
|----------|-------------|
| `prompt_techniques.ipynb` | Comprehensive guide to prompt strategies: zero-shot, few-shot, chain-of-thought, and more |

**Key Topics:** Zero-shot Prompting, Few-shot Prompting, Chain-of-Thought, Prompt Templates, Output Parsing

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/aljebraschool/GenerativeAI-Bootcamp.git
cd GenerativeAI-Bootcamp
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate        # macOS / Linux
# venv\Scripts\activate          # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory:

```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name
HF_TOKEN=your_huggingface_token
GROQ_API_KEY=your_groq_api_key
```

> ⚠️ **Important:** Never commit your `.env` file to version control. It is already included in `.gitignore`.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Navigate to the desired week's folder and open the notebooks in order.

---

## Environment Variables

This project uses API keys from several providers. You'll need to sign up and obtain keys from:

| Variable | Provider | Purpose | Sign Up |
|----------|----------|---------|---------|
| `OPENAI_API_KEY` | OpenAI | GPT models, embeddings | [platform.openai.com](https://platform.openai.com/) |
| `LANGCHAIN_API_KEY` | LangChain | LangSmith tracing & monitoring | [smith.langchain.com](https://smith.langchain.com/) |
| `LANGCHAIN_PROJECT` | LangChain | Project name for LangSmith | — |
| `HF_TOKEN` | HuggingFace | Model access & embeddings | [huggingface.co](https://huggingface.co/) |
| `GROQ_API_KEY` | Groq | Fast LLM inference | [console.groq.com](https://console.groq.com/) |

---

## Technologies & Libraries

| Category | Technologies |
|----------|-------------|
| **Language** | Python 3.9+ |
| **Deep Learning** | TensorFlow, tf-keras |
| **NLP** | NLTK, HuggingFace Transformers, Sentence-Transformers |
| **LLM Framework** | LangChain, LangChain Community, LangChain Core, LCEL |
| **LLM Providers** | OpenAI, Groq, HuggingFace |
| **Vector Stores** | Chroma, FAISS |
| **Data & ML** | Pandas, Scikit-learn |
| **Monitoring** | TensorBoard, LangSmith |
| **Utilities** | python-dotenv, Wikipedia, Arxiv |

---

## Contributing

Contributions are welcome! If you'd like to improve existing notebooks or add new content:

1. **Fork** this repository
2. **Create** a feature branch: `git checkout -b feature/your-feature-name`
3. **Commit** your changes: `git commit -m "Add: description of your changes"`
4. **Push** to your branch: `git push origin feature/your-feature-name`
5. **Open** a Pull Request

Please ensure your notebooks are well-documented and follow the existing structure.

---

## License

This project is open source and available for educational purposes. Feel free to use, modify, and distribute the materials with proper attribution.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/aljebraschool">aljebraschool</a>
</p>
