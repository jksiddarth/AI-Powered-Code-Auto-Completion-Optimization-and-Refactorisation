# AI-Powered-Code-Auto-Completion-Optimization-and-Refactorisation
This project demonstrates the development of an intelligent code assistant that uses transformer-based Natural Language Processing (NLP) models to understand user prompts written in plain English and generate, optimize, or refactor Python code. Leveraging GPT-Neo 1.3B and integrated with Gradio for a clean browser interface, the solution is also extended to Android devices through a native app using WebView. This makes AI-assisted programming accessible, flexible, and mobile-ready.

---

## 📌 Motivation
In the modern software development landscape, automation is key to enhancing productivity and reducing time-to-code. Writing boilerplate code, optimizing algorithms, and maintaining code quality are repetitive yet critical tasks. This project explores how artificial intelligence, specifically transformer-based language models, can assist developers by automating these tasks using natural language instructions.

By bridging the gap between human language and executable code, the AI assistant reduces development time, supports beginners in learning programming, and aids professionals in quickly iterating over solutions.

---

## 🎯 Project Objectives
- To develop an AI-driven system that interprets natural language and generates executable Python code.

- To implement automatic optimization mechanisms that enhance performance, memory usage, and runtime efficiency.

- To integrate automatic code refactoring that improves readability, modularity, and overall maintainability.

- To deploy the assistant as both a Gradio web interface and a mobile Android application for greater accessibility.

---

# 🚀 Key Features
- Natural Language to Code: Simply type “Write a function to reverse a string,” and the system returns the corresponding Python code.

- Code Optimization: Paste your existing function, and the AI suggests a more efficient version.

- Refactoring Capabilities: Improve code readability and structure while keeping the logic unchanged.

- Interactive Gradio Interface: Clean, intuitive web UI that works out-of-the-box.

- Android Application: Access the assistant from your phone using a minimal native app that wraps the Gradio interface.

---

# 💻 Technologies Used
GPT-Neo 1.3B - Transformer-based language model used for text/code generation
Hugging Face Transformers	- Model loading and pipeline management
Gradio -	Web interface for user interaction
Python	- Backend logic and prompt formatting
PyTorch	- Deep learning model execution framework
Android Studio - (Java)	Embeds the Gradio UI into a native Android app via WebView

---

## 🛠️ How It Works
- User Input: The user provides a task description or existing code via CLI, Gradio UI, or Android App.

- Prompt Construction: The prompt is formatted with proper structure to guide the AI model.

- Model Inference: The GPT-Neo model processes the prompt and generates output (new code, optimized, or refactored).

- Postprocessing: The output is cleaned and formatted before being returned to the user.

- Display: The code is displayed on-screen in the interface, ready to be used or tested.

---

## ✅ Results & Observations
- The model can successfully interpret user requests and provide useful Python code in most cases.

- Optimizations improve structure and performance in many simple tasks.

- Refactorization helps make code more readable but may not always include comprehensive improvements.

- Real-time AI interaction through both browser and Android platforms improves accessibility and user experience.
