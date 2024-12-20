# LLM-Toolbox

This application explores how to build a comprehensive API that leverages LLMs for content generation, financial analysis, scientific paper processing, and more. 

![imagen](https://github.com/user-attachments/assets/b0fa731c-b6e7-4c55-bcb7-b7883880377c)

A full article describing the app can be found in:

https://medium.com/@joserodr68/building-a-versatile-llm-toolbox-with-fastapi-and-crewai-809ea15c48ba

## Architecture Overview
The LLM Toolbox is a FastAPI and React based application that provides multiple services:
- Blog and social media content generation
- Financial news and stock market analysis
- Scientific paper processing and querying
- Financial News and Stock Fundamental and Technical analysis
- Image generation via retrieval


## Prerequisites

- Python 3.11
- pip or conda for package management
- Node.js 

## Installation

1. Clone this repository:
```bash
git clone https://github.com/joserodr68/LLM-Toolbox.git
cd LLM-Toolbox
```

2. Create and activate a virtual environment (optional):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install crewai langchain openai fastapi uvicorn llama-index
```
The full requirements.txt file is available within the `backend` folder.

## Environment Setup

Create a `.env` file in the project `backend` folder with your API keys:

```
OPENAI_API_KEY=your_openai_api_key_here
SERPER_API_KEY=your_serper_api_key_here  # used for web search
GROQ_API_KEY=your_groq_api_key_here
```

## React Front End

Refer to the instructions in the `frontend` folder's `README.md` file to launch the application.

## Launch the FastAPI Backend

```bash
python main.py
```
## Run with Docker

Both the front-end and back-end can be run in their respective Docker containers. Dockerfiles are provided in each folder.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request


