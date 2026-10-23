# LangChain – From Basics to Building GenAI Applications 🚀

Welcome to my LangChain learning repository!

This repository documents my hands-on journey of learning **LangChain**, a framework for developing applications powered by Large Language Models (LLMs).

The goal of this repository is to understand LangChain concepts through simple explanations, practical Python examples, and progressively more advanced implementations.

Whether you're a beginner exploring Generative AI or someone looking to strengthen your LangChain fundamentals, feel free to explore, learn, and code along!

---

## 📌 About This Repository

This repository contains my practice implementations while exploring different components of LangChain.

Rather than focusing only on theoretical concepts, I'm learning by writing code, experimenting with different models, and understanding how individual components work together to build real-world GenAI applications.

## 📂 Repository Structure

```text
LangChain/
│
├── 1.LLMs/
├── 2.ChatModels/
├── 3.EmbeddingModels/
├── Chains/
├── Document_Loaders/
├── Output_Parsers/
├── Prompts/
├── Runnables/
├── Structured_Output/
├── Text_Splitters/
│
├── requirements.txt
├── test.py
└── README.md
```

## 📚 Topics Covered

| Topic | What You'll Learn |
|---|---|
| LLMs | Understanding and interacting with Large Language Models |
| Chat Models | Working with conversational AI models |
| Embedding Models | Converting text into numerical vector representations |
| Prompts | Creating dynamic and reusable prompt templates |
| Chains | Connecting multiple components into workflows |
| Output Parsers | Extracting and formatting LLM responses |
| Structured Output | Generating responses in predefined formats |
| Runnables | Building modular workflows using LangChain |
| Document Loaders | Loading data from external documents |
| Text Splitters | Splitting large documents into manageable chunks |

Each folder contains Python implementations related to its respective topic.

---

## 🛠️ Technologies Used

- Python
- LangChain
- OpenAI API
- Google Gemini
- Anthropic
- Hugging Face
- Python-dotenv
- VS Code

*Note: Different examples may require different model providers and API keys.*

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

### 2. Create a Virtual Environment

```bash
py -m venv .venv
```

Activate the environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

For macOS/Linux:

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory.

Add the API keys required by the examples you want to run:

```env
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
GOOGLE_API_KEY=your_google_api_key
```

**Important:** Never upload your `.env` file or actual API keys to GitHub.

### 5. Run an Example

Navigate to the relevant folder and execute the Python script.

For example:

```bash
python "1.LLMs/llm_demo.py"
```

*Replace the filename with the actual script available in the folder.*

---

## 🎯 Learning Objectives

Through this repository, I aim to:

- Build a strong foundation in LangChain.
- Understand how LLM-powered applications work.
- Explore different language models and their integrations.
- Learn how to design reusable AI workflows.
- Work with embeddings and document-processing techniques.
- Progress towards building Retrieval-Augmented Generation (RAG) applications and AI agents.
- Apply these concepts to real-world Generative AI projects.

## 🚀 What's Next?

As I continue learning, I plan to expand this repository with:

- Vector Databases
- Retrieval-Augmented Generation (RAG)
- Conversational AI
- Tool Calling
- AI Agents
- LangGraph
- End-to-End GenAI Projects

## 📖 Learning Resources

Some useful resources for anyone getting started:

- [LangChain Official Documentation](https://docs.langchain.com/)
- [LangChain GitHub](https://github.com/langchain-ai/langchain)
- [Python Documentation](https://docs.python.org/3/)
- [Hugging Face](https://huggingface.co/learn)

## 🤝 Contributions

This repository is part of my continuous learning journey.

If you find an issue, have suggestions, or want to improve an example, feel free to open an issue or submit a pull request.

Contributions and constructive feedback are always welcome!

---

### ⭐ Support

If you find this repository useful for your own LangChain learning journey, consider giving it a star!

**Happy Learning & Building! 🚀**
