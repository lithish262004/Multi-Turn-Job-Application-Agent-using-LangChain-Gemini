
# 🤖 Multi-Turn Job Application Agent using LangChain & Gemini (Colab-Ready)

This project builds a smart AI assistant that can **converse over multiple turns** to help users apply for jobs — by generating resumes, writing cover letters, and managing application details — all from an interactive **Gradio interface** running in **Google Colab**.

## 📌 Key Features

- 🧠 **Multi-turn Conversations** with memory (LangChain + Gemini)
- 🎯 **Intent Detection** (e.g., “I want to apply for a Data Analyst job”)
- 📄 **Resume Builder**: Dynamically generate role-based resumes
- ✉️ **Cover Letter Generator** using your experience and resume
- 🧰 **Tool Calling**: Save structured application details
- 🌐 **Gradio UI**: Simple, interactive web app inside Colab

**⚙️ Setup Instructions (Google Colab)
1.Install Required Packages**
!pip install langchain langchain-google-genai google-generativeai gradio python-dotenv pydantic

**2. Set Google Gemini API Key**
import os
from getpass import getpass
os.environ["GOOGLE_API_KEY"] = getpass("Enter your Google GenerativeAI API Key: ")

**3.Run the Gradio App**

** Sample Interaction**
👤 User: I want to apply for a Backend Developer role.
🤖 Agent: Great! Tell me about your experience, skills, and education.
👤 User: I have 2 years of experience in Django, and I studied B.Tech in IT.
🤖 Agent: Here's your tailored resume and a draft cover letter!

**📌 Tech Stack**
LLM: Google Gemini via langchain-google-genai
Framework: LangChain (agent, tools, memory)
UI: Gradio (Colab-compatible)
Others: Pydantic, dotenv

