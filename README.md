# Smart Study With RAG

[![Python Version](https://img.shields.io/badge/python-3.12%2B-blue.svg)](https://www.python.org/downloads/)
[![Project Version](https://img.shields.io/badge/version-0.1.0-green.svg)](https://github.com/ufmg/evolutionary-fsm-agentic-control/releases)
[![OpenAI](https://img.shields.io/badge/OpenAI-powered-purple.svg)](https://docs.crewai.com/)
<!-- [![LangChain](https://img.shields.io/badge/LangChain-powered-blueviolet.svg)](https://www.langchain.com/) -->
<!-- [![CREWAI](https://img.shields.io/badge/CrewAI-powered-magenta.svg)](https://docs.crewai.com/) -->

> An Answering System on Private Documents.


## Quick Start
### Prerequisites
- Python 3.12+
- [uv](https://docs.astral.sh/uv/) package manager

### Installation
1. **Clone the repository:**
```bash
$ git clone git@github.com:leandrofahur/smart-study-with-rag.git
$ cd smart-study-with-rag
```

2. **Create virtual environment:**
```bash
$ uv venv --python 3.12
```

3. **Activate virtual environment:**
```bash
$ source .venv/bin/activate
```

4. **Install dependencies:**
```bash
$ uv sync
```


## 📁 Project Structure
```bash
.smart-study-with-rag/
├── .venv/                   # Virtual environment
├── .python-version          # Python version specification
├── pyproject.toml           # Project configuration
├── uv.lock                  # Dependency lock file
├── main.py                  # Main entry point
├── ... 
├── LICENSE                  # Project license
└── README.md                # This file
```


### Running Examples
```bash
# Run main entry point
$ python main.py
```


## 📄 License
This project is licensed under the terms specified in the [LICENSE](LICENSE) file.


## Troubleshooting
### Common Issues
**Python version not found:**
```bash
# Remove .python-version if causing conflicts
$ rm .python-version

# Create venv with specific Python version
$ uv venv --python 3.12
```

**Dependencies not found:**
```bash
# Reinstall dependencies
$ uv sync --reinstall
```

**Virtual environment issues:**
```bash
# Remove and recreate virtual environment
$ rm -rf .venv
$ uv venv
$ uv sync
```


## Contributors
We welcome all contributors! Here are our current team members:

| Avatar | Name | Role | GitHub |
|--------|------|------|--------|
| <img src="https://avatars.githubusercontent.com/u/46628080?u=7c2c2d90408b1a731118b5b3512d9da890cf2d45&v=4" width="40" /> | **Leandro Miranda Fahur Machado** | Software Engineer | [@leandrofahur](https://github.com/leandrofahur) |