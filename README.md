# educhatbot

This project implements the chatbot about the smart choice program.

The questions and answers data are scraped from https://education.qld.gov.au/students/student-health-safety-wellbeing/student-health/smart-choices/faq by [BrowerAI](https://www.browse.ai/) 
The vector store has been created by using OpenAIembeddings. 
GUI - [Gradio](https://www.gradio.app/)

Setup 
1. create .env file in project folder and setup openai API key (eg. OPENAI_API_KEY=sk-)
2. Run ChatBot.py
