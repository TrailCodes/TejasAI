# AI Agent Researcher 🤖

An intelligent, multi-agent AI system designed to automate and accelerate academic and industrial research by autonomously analyzing vast information sources, synthesizing findings, and generating novel research hypotheses.

# Dependices To Install

## Dependencies

This project relies on the following Python packages:

* **[arxiv](https://pypi.org/project/arxiv/)** `>=2.2.0` – Access and query arXiv papers.
* **[langchain](https://pypi.org/project/langchain/)** `>=0.3.27` – Framework for building LLM-powered applications.
* **[langchain-core](https://pypi.org/project/langchain-core/)** `>=0.3.78` – Core utilities for LangChain integrations.
* **[langchain-google-genai](https://pypi.org/project/langchain-google-genai/)** `>=2.1.12` – Google Generative AI integration for LangChain.
* **[langgraph](https://pypi.org/project/langgraph/)** `>=0.6.8` – Graph-based workflow framework for LangChain.
* **[pylatex](https://pypi.org/project/PyLaTeX/)** `>=1.4.2` – Generate LaTeX code and PDFs.
* **[pypdf](https://pypi.org/project/pypdf/)** `>=6.1.1` – Work with PDF files (reading, writing, merging).
* **[pypdf2](https://pypi.org/project/PyPDF2/)** `>=3.0.1` – Alternative PDF library for reading and editing PDFs.
* **[python-dotenv](https://pypi.org/project/python-dotenv/)** `>=1.1.1` – Load environment variables from `.env` files.
* **[reportlab](https://pypi.org/project/reportlab/)** `>=4.4.4` – PDF generation library.
* **[requests](https://pypi.org/project/requests/)** `>=2.32.5` – HTTP requests made simple.
* **[rich](https://pypi.org/project/rich/)** `>=14.1.0` – Rich text and beautiful formatting in the terminal.
* **[typing-extensions](https://pypi.org/project/typing-extensions/)** `>=4.15.0` – Backported typing features for compatibility.

## 🚀 Getting Started

Follow these steps to set up the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/TrailCodes/TejasAI.git
```
### 2.1 Install uv for windows
```powershell
 -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
### 2.2 Install uv on macOS and Linux
```curl
 -LsSf https://astral.sh/uv/install.sh | less
```
### 3. Install dependencies with [uv]

```bash
uv pip install -r requirements.txt
```

### 3. Create .env file

GOOGLE_API_KEY = your gemini_api_key

### 4.Install tectonic

[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072
iex ((New-Object System.Net.WebClient).DownloadString('https://drop-ps1.fullyjustified.net'))

### 5. To Run the Project

```bash
uv run ai_researcher.py
```
Watch the video demo:-
(https://github.com/TrailCodes/TejasAI/raw/main/Hacify_TechNova.mp4)
