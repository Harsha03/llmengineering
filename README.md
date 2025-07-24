---

Welcome to **LLM Engineering**! This repository contains interactive Jupyter notebooks that showcase advanced generative AI workflows for web automation, conversational AI, and knowledge retrieval.

## 📚 Notebooks Overview

### 1. 🚀 llmwebscraper.ipynb
- **Purpose:** Automate the creation of company brochures using generative AI.
- **Features:**
  - Scrapes website content and relevant links
  - Uses OpenAI's API for content analysis
  - Generates entertaining, informative, markdown-formatted brochures
  - Demonstrates prompt engineering and real-time streaming of AI-generated text
- **Use Case:** Practical guide for building GenAI-powered web automation workflows

### 2. 💬 llmchatbot.ipynb
- **Purpose:** Build a multi-model AI chatbot with Gradio.
- **Features:**
  - Streams responses from OpenAI GPT, Anthropic Claude, and Google Gemini
  - Model selection for real-time interaction
  - User-friendly Gradio web interface
  - Highlights prompt engineering and streaming LLM outputs
- **Use Case:** Advanced conversational AI applications

### 3. 📝 llmmeetingminutes.ipynb
- **Purpose:** Automate the transcription and summarization of meeting audio into structured minutes.
- **Features:**
  - Uses OpenAI Whisper for audio-to-text transcription
  - Integrates HuggingFace pipelines for LLM inference
  - Employs advanced tokenizers for prompt formatting and streaming output
  - Authenticates with HuggingFace Hub and OpenAI for secure API access
  - Generates meeting minutes with summaries, key points, takeaways, and action items
- **Use Case:** End-to-end automation of meeting minutes from audio files

### 4. 🧠 llmknowledgeworker.ipynb
- **Purpose:** Demonstrate Retrieval-Augmented Generation (RAG) using LangChain and Chroma.
- **Features:**
  - Loads and splits documents from a local knowledge base located in the `src/knowledge-base` folder
  - Creates vector embeddings with OpenAI
  - Stores embeddings in a Chroma vector database
  - Builds a conversational retrieval chain with LangChain
  - Enables querying the knowledge base with an LLM for contextually relevant answers
  - Real-time Gradio chat interface for RAG-powered assistant
- **Use Case:** Knowledge retrieval and conversational AI with RAG

---

