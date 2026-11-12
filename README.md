# AI-Study-Assistant-Powered-by-Gemini


# 🤖 AI Study Assistant – Powered by Google Gemini

## 📌 Project Overview

AI Study Assistant is a beginner-friendly AI-powered application developed using Python and Google Gemini API. It helps students learn concepts, understand difficult topics, generate Python programs, and practice quizzes through an interactive interface.

The project is developed in **Google Colab** as part of an AI Tools and Mini Project learning milestone.

## 🎯 Objectives

- Explore Generative AI tools such as ChatGPT and Google Gemini.
- Understand how AI can improve learning and productivity.
- Build an AI-powered application using Python.
- Practice prompt engineering and API integration.
- Generate educational content automatically.

## ✨ Features

The application provides four main functionalities:

1. **Explain:** Explains difficult topics in simple language with examples.
2. **Summarize:** Converts lengthy topics into short and understandable notes.
3. **Python Code:** Generates Python programs based on user requirements.
4. **Quiz:** Creates practice questions to improve student knowledge.

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Google Gen AI SDK
- Google Colab
- Generative AI
- Prompt Engineering

## ⚙️ How It Works

1. The user opens the AI Study Assistant.
2. The application displays four available options.
3. The user selects a task.
4. The user enters a topic or question.
5. The Python application sends the prompt to the Gemini API.
6. Gemini processes the request and generates a response.
7. The result is displayed in Google Colab.

## 📥 Sample Input

```text
===== AI STUDY ASSISTANT =====

1. Explain
2. Summarize
3. Python Code
4. Quiz

Choose an option (1-4): 1

Enter your topic or question: What is Artificial Intelligence?
```

## 📤 Expected Output

```text
===== AI RESPONSE =====

Artificial Intelligence (AI) is a technology
that enables computers to perform tasks that
normally require human intelligence.

Examples:
1. Chatbots
2. Voice assistants
3. Self-driving cars
4. Recommendation systems
```

*Note: Actual responses are generated dynamically by the Gemini API.*

## 🚀 How to Run the Project

### Step 1: Open Google Colab

Visit https://colab.research.google.com/

### Step 2: Create a Notebook

Create a new Python notebook.

### Step 3: Install the required package

```python
!pip install -q -U google-genai
```

### Step 4: Configure Gemini API

1. Get an API key from https://aistudio.google.com/app/apikey
2. Open the Secrets panel in Google Colab.
3. Add a secret named `GEMINI_API_KEY`.
4. Paste your API key as its value.
5. Enable notebook access.

### Step 5: Connect the API

```python
from google import genai
from google.colab import userdata

api_key = userdata.get("GEMINI_API_KEY")
client = genai.Client(api_key=api_key)
```

### Step 6: Run the Project

Run all notebook cells, select an option, enter your question, and view the generated AI response.

## 🔐 Security

- API keys are stored using Google Colab Secrets.
- Never upload API keys to GitHub.
- Never share your private API credentials.

## 🌱 Future Enhancements

- Add a graphical user interface.
- Add voice-based question input.
- Save previous learning conversations.
- Support multiple languages.
- Add interactive quiz scoring.
- Integrate more AI models.

## 🎓 Learning Outcomes

Through this project, I learned:

- How to integrate a Generative AI API with Python.
- How to write effective prompts.
- How to build an interactive Python application.
- How to use AI for education and productivity.
- How to work with Google Colab and external libraries.

## 👩‍💻 Author

**Ch Sridevi**

AI & Data Science Student

GitHub: https://github.com/chsridevi03

---

⭐ If you find this project useful, consider giving the repository a star!

**Project:** AI Study Assistant – Powered by Google Gemini  
**Category:** Artificial Intelligence | Generative AI | Python Mini Project
```

