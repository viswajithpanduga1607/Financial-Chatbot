# Financial-Chatbot
## Project Overview
This repository contains the source code for an Intelligent Financial Chatbot, developed as part of the AI-Powered Project Development assignment. The application addresses the real-world problem of financial literacy by providing users with instant, objective, and accurate guidance on budgeting, savings, loans, investments, and financial planning.

## Features and Functionality
* **Conversational Interface:** A sleek, user-friendly chat UI built with Gradio that allows users to interact naturally.
* **Context-Aware Responses:** Maintains chat history to provide conversational continuity across multi-turn financial inquiries.
* **Framework-Based Guidance:** Programmed to apply established financial models, such as the 50/30/20 budgeting rule and compound interest principles.
* **Out-of-Domain Redirection:** Automatically recognizes non-financial queries and politely redirects users back to core financial topics.

## Benefits
* **Accessibility:** Democratizes access to financial planning logic, acting as an educational tool for personal finance management.
* **Efficiency:** Instantly breaks down complex financial jargon (e.g., fixed vs. variable interest rates) into understandable concepts.
* **Scalability:** The cloud-native architecture allows the chatbot to handle a limitless number of queries simultaneously without performance degradation.

## How AI is Utilized
This project leverages the **Google Gemini (gemini-1.5-flash) Large Language Model (LLM)** via the `google-generativeai` SDK. 
AI is specifically used for Natural Language Processing (NLP) to parse user intent and generate human-like, structured responses. The model's behavior is strictly governed by a **System Prompt** (Persona Constraint) that forces the AI to act exclusively as a professional financial advisor. This system-level instruction ensures the AI formats its advice clearly, relies on objective financial mathematics, and includes necessary disclaimers regarding certified financial planning.

## Sample Data and Testing Prompts
The application comes pre-loaded with sample prompts to demonstrate its capabilities. To test the system, try inputting the following sample data:
1. *Budgeting:* "I make $4,000 a month. Can you create a 50/30/20 budget for me?"
2. *Loans:* "What is the difference between a fixed and variable rate loan?"
3. *Investing:* "How much will I have in 10 years if I invest $500 a month at a 7% annual return?"
4. *Security:* "What are some common signs of credit card fraud I should look out for?"

## Setup and Installation
This project is designed to run in a Jupyter Notebook environment such as Google Colab.

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
