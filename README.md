# 🧠 Chat with Einstein – Gemini AI Chatbot

An interactive AI chatbot that answers questions **as Albert Einstein**, combining reasoning, personal anecdotes, and a touch of humor.  
Built with **Google Gemini**, **LangChain**, and **Gradio**.

---

## ✨ Features

- 🤖 AI persona of **Albert Einstein**
- 🧩 Answers include reasoning, curiosity, and personal stories
- 😄 Light humor and conversational tone
- 💬 Chat history support
- 🌐 Web-based UI using **Gradio**
- ⚡ Powered by **Gemini 2.5 Flash**

---

## 🛠️ Tech Stack

- Python 3.9+
- Google Gemini API
- LangChain
- Gradio
- python-dotenv

---

## 📂 Project Structure

.
├── gemini_bot.py        # Main application file
├── einstein.png         # Avatar image (optional)
├── .env                 # Environment variables (not committed)
└── README.md


---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
### 2️⃣ Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```
### 3️⃣ Install dependencies
```bash
pip install gradio langchain langchain-google-genai python-dotenv
```
### 4️⃣ Set environment variables
Create a .env file in the project root:
```bash
GEMINI_API_KEY=your_google_gemini_api_key
```
### ▶️ Run the App
```bash
python gemini_bot.py
```
After launch, Gradio will provide a local (and shareable) URL.
Open it in your browser and start chatting with Einstein 🧑‍🔬✨

## 🧠 How It Works

- Uses **LangChain** to manage prompt templates and chat history
- A system prompt defines Einstein’s personality and behavior
- Chat history is converted into LangChain message objects
- Responses are generated via **ChatGoogleGenerativeAI**
- UI is built using **Gradio Blocks**

## 🔮 Future Improvements

- Streamed / real-time responses
- Support for multiple historical personas
- Per-session or long-term memory
- Dockerized setup for easier deployment
- Cloud deployment (Hugging Face Spaces, Cloud Run, etc.)

## 📜 License

This project is provided for educational and experimental purposes.  
You are free to use, modify, and distribute this project as you see fit.


