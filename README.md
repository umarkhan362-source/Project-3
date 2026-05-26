# Project-3
# Gemini AI Chatbot Notebook

## Overview

This project demonstrates how to build AI-powered chatbot applications using the Google Gemini API in Python. The notebook covers the basics of API integration, conversational AI, system prompts, and specialized assistants such as an HR assistant and a customer support bot.

The project is implemented in a Jupyter Notebook (`week9t.ipynb`) and is designed for learning conversational AI development with Gemini 2.5 Flash.

---

# Features

* Gemini API integration using Python
* Secure API key management with Kaggle Secrets
* Basic AI text generation
* Interactive chatbot conversation loop
* System prompt customization
* HR Assistant chatbot
* Customer Support chatbot
* Configurable AI parameters such as:

  * Temperature
  * Max output tokens
  * System instructions

---

# Technologies Used

* Python
* Google Gemini API
* Jupyter Notebook
* Kaggle Secrets
* `google-genai` library
* `python-dotenv`

---

# Installation

Install the required dependencies:

```bash
pip install openai python-dotenv
```

Install the Gemini SDK:

```bash
pip install google-genai
```

---

# Project Structure

```text
week9t.ipynb
README.md
```

---

# Tasks Covered

## Task 1.1 – Environment Setup

* Install required libraries
* Configure API access
* Initialize Gemini client

## Task 1.2 – First API Call

* Generate a simple AI response
* Learn how Gemini handles prompts and responses

## Task 2.1 – Conversation Loop

* Build an interactive chatbot
* Maintain conversational flow
* Accept continuous user input

## Task 2.2 – System Prompt

* Add custom chatbot instructions
* Control chatbot personality and behavior

## Task 3.1 – HR Assistant

* Create a policy-based HR chatbot
* Answer employee-related questions
* Use structured system prompts

## Task 3.2 – Customer Support Bot

* Build an e-commerce support assistant
* Handle customer queries professionally
* Demonstrate empathy and escalation handling

---

# Example Usage

```python
response = client.models.generate_content(
    model='gemini-2.5-flash',
    contents='Say hello and introduce yourself!'
)

print(response.text)
```

---

# Learning Outcomes

After completing this project, you will understand:

* How to use the Gemini API
* How conversational AI systems work
* How system prompts influence AI behavior
* How to create domain-specific assistants
* How to manage chatbot conversations in Python

---

# Future Improvements

* Add GUI interface using Streamlit or Flask
* Connect chatbot with databases
* Add speech-to-text support
* Deploy chatbot online
* Integrate memory and context storage

---

# Author

Developed as a learning project for understanding Generative AI and conversational chatbot systems using Google Gemini.
