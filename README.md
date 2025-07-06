
# 🧠 Prabhas Personal AI Agent (Groq + LLaMA 3)

This is a simple conversational AI agent that reads your personal profile from a `.docx` file and uses Groq's blazing-fast **LLaMA 3** API to respond intelligently to questions about you.

## 🚀 Features

- Loads your resume/profile from a Word document.
- Uses `llama3-70b-8192` via the **Groq API**.
- Maintains full conversation history (like a real chatbot).
- Runs locally in the terminal.
- Clean and minimal Python code.

## ⚙️ Requirements

- Python 3.7+
- Install required packages:
```bash
pip install python-docx openai

🔑 Setup

1. Create an account at https://console.groq.com.


2. Get your Groq API Key.


3. Replace the line 



api_key = "REPALCE_WITH_YOUR_GROQ_API"

with your actual key.

4. Make sure RESUME.docx is in the same directory as your script.

🧪 Running the Agent

You will now enter a chat loop:

🤖 You can now chat with your AI agent! (type 'exit' to stop)

You: What are Prabhas's main skills?
AI: Prabhas specializes in Python, Data Science, and AI-powered tools...


---

🛠 Customization

Replace prabhas_profile.docx with your own DOCX resume or profile.

Customize the system prompt in the messages list to adjust behavior.

Add logging, memory saving, or chatbot UI if needed.



---

🧠 Powered By

🦙 LLaMA 3 (70B) via Groq API

📄 python-docx for reading .docx files

💬 OpenAI-compatible API calls


🙋‍♂️ Author

Prabhas Naidu
AI enthusiast | Developer | Innovator

