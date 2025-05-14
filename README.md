# Project4-Priyanshi
# 🏛️ Chatbot for E-Government Services

A conversational chatbot built using Flask, OpenAI, and LangChain to assist users with common queries related to government services. The chatbot automates responses for tasks like applying for PAN cards, checking Aadhaar status, and passport renewal.

---

## 🚀 Features

- 🔍 Understands queries like:
  - "How to apply for a PAN card?"
  - "Check passport renewal process"
  - "Update Aadhaar address online"
- 💬 Built with OpenAI + LangChain for smart, real-time responses
- 🌐 Simple and responsive web interface using Flask
- 🧠 Modular code: easy to extend and integrate with real government APIs

---

## 🛠️ Tech Stack

- Python
- Flask
- LangChain
- OpenAI API (GPT)
- HTML/CSS

---

## 🧾 File Structure
Chatbot-for-E-Government/
├── app.py # Flask backend server
├── chat.py # Chatbot logic using LangChain
├── requirements.txt # Dependencies
├── templates/
│ └── chat.html # Web interface (chat UI)
├── static/
│ └── style.css # CSS for chat interface
├── .env.example # Template for storing OpenAI API key


## 🧪 How to Run Locally

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/e-gov-chatbot.git
cd e-gov-chatbot
2. Install Dependencies
pip install -r requirements.txt
3. Add Your OpenAI API Key
Create a file named .env in the root directory with:
OPENAI_API_KEY=your_api_key_here
4. Run the App:-
python app.py


📌 Future Scope
🔗 Integration with real e-governance APIs
🌍 Multilingual support (Hindi, regional languages)
🛡️ Secure authentication for user-specific services

🙏 Acknowledgement
Based on ashhass/Chatbot
Extended and customized for e-governance use cases.
