# 🤖 GenAI Chatbot (Streamlit + Google Gemini)

A modern AI chatbot web application built using **Streamlit** and **Google Gemini API**.
This project demonstrates how to integrate Generative AI into an interactive web interface with session-based chat memory.

---

## 🚀 Features

* 💬 Interactive chat interface (like ChatGPT)
* 🧠 Maintains conversation history (session memory)
* ⚡ Fast responses using Gemini models
* 🔐 Secure API key handling using environment variables / Streamlit secrets
* 🌐 Deployable on Streamlit Cloud

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Google Generative AI (Gemini API)**
* **python-dotenv**

---

## 📂 Project Structure

```
GenAI-chat-application/
│── app.py              # Main Streamlit app
│── requirements.txt    # Dependencies
│── .gitignore          # Ignored files
│── .env                # API key (not pushed to GitHub)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/genai-chatbot-streamlit.git
cd genai-chatbot-streamlit
```

---

### 2️⃣ Create virtual environment

```
py -m venv venv
venv\Scripts\activate
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Add API Key

Create a `.env` file in the root directory:

```
GENAI_API_KEY=your_api_key_here
```

---

### 5️⃣ Run the app

```
streamlit run app.py
```

---

## 🌐 Deployment (Streamlit Cloud)

1. Push code to GitHub
2. Go to Streamlit Cloud
3. Deploy your repo
4. Add secret:

```
GENAI_API_KEY = "your_api_key_here"
```

---

## 🧠 How It Works

1. User enters a message
2. Message is stored in `session_state`
3. Full conversation is sent to Gemini API
4. AI response is generated and displayed
5. Chat history is preserved for context

---

## 🚀 Future Improvements

* 🔄 Streaming responses (real-time typing effect)
* 🧹 Clear chat button
* 📊 Sidebar controls
* 🎨 Enhanced UI/UX
* 🧠 Long-term memory support

## 👨‍💻 Author

**Sahil Kumar**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
