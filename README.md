# Secure Local Code Assistant with Ollama

![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-orange)
![Privacy](https://img.shields.io/badge/Privacy-100%25_Local-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## About the Project

The **Secure Local Code Assistant** is an AI-powered developer tool designed to execute entirely on your local machine using [Ollama](https://ollama.ai/). This assistant provides intelligent code generation, debugging, and refactoring without ever sending your proprietary source code or intellectual property to third-party cloud servers.

By ensuring a 100% air-gapped, local inference environment, this tool meets strict enterprise security and data compliance requirements while delivering state-of-the-art developer assistance using models like `codellama`, `deepseek-coder`, or `llama3`.

### Core Features
* **Zero Cloud Dependency:** Complete privacy. No telemetry, no API payloads, no data leaks.
* **Context-Aware Assistance:** Read and analyze local project files securely to provide context-driven code solutions.
* **Streaming Responses:** Real-time token generation for a seamless UI experience.
* **Customizable Prompts:** Easily modify system prompts to tailor the assistant to specific languages or frameworks.

## Prerequisites

1. **Python 3.9+**
2. **Ollama:** Must be installed and running on your local machine. ([Download Ollama](https://ollama.ai/download))
3. **Local LLM Models:** Pull your preferred coding model before running the app.
```bash
   ollama pull deepseek-coder  # or codellama, llama3, etc.
```

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/Harsh-7612/secure-local-code-assistant-with-ollama.git](https://github.com/Harsh-7612/secure-local-code-assistant-with-ollama.git)
   cd secure-local-code-assistant-with-ollama
   ```
2. Setup virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Ensure the Ollama background service is running on your machine.
2. 
