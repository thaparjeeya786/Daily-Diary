# Artificial Intelligence & Machine Learning Training Report - Day 19
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 17 July 2025  

## Overview
Today, I explored the frontend setup for running LLaMA models in a local environment. I learned how to interact with models such as TinyLLaMA through a simple browser-based interface using Ollama and local web frontends (running on `localhost`). This approach makes working with LLaMA models more user-friendly compared to the command line.

## Learning Objectives
- Understand what the LLaMA frontend is and how it works.  
- Learn how to interact with LLaMA models using a web-based interface.  
- Explore the setup process for running LLaMA with Ollama locally.  
- Know the basic commands for installing, pulling, and running LLaMA models.  
- Understand how the frontend communicates with the backend through API calls.  

## LLaMA Frontend
The LLaMA Frontend is a web interface that allows users to chat with LLaMA models easily.  
- Instead of using command-line inputs, prompts are entered directly in a browser.  
- Useful for running models like LLaMA 2, TinyLLaMA, or CodeLLaMA locally.  
- Can be customized with tools like Flask or Text Generation WebUI.  


## Implementation Tools
- **Ollama** – To run LLaMA models locally.  
- **Flask / Node.js** – Backend (if building a custom frontend).  
- **HTML, CSS, JavaScript** – For frontend design.  
- **Localhost** – Where the frontend runs (`http://localhost:11434` by default).  


## Basic Commands and Setup
### Install Ollama
```bash
curl -fsSL https://ollama.com/install.sh | sh
```
## Pull and Run a LLaMA Model (e.g., TinyLLaMA)
```bash
ollama pull tinyllama
ollama run tinyllama
```

## Run a Frontend App with Flask
```bash
python app.py
```
### Conclusion

Today I learned how to make LLaMA models more accessible through a browser-based frontend. Instead of relying only on command-line tools, I now know how to build or use a simple web interface to interact with AI models. This improves user experience and opens the door for creating real-world applications like chatbots, educational assistants, and productivity tools.
