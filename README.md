
# 🤖 Gemini AI Assistant (CLI + GUI)

> A sleek Python-based AI assistant powered by Gemini API with both CLI and GUI interfaces.

---

## ✨ Features

- 💬 Answer factual questions  
- 📝 Summarize text  
- 🎨 Generate creative content  
- 🎯 Provide productivity & study advice  
- 🖥️ Dual Interface:
  - CLI (Terminal-based)
  - GUI (Tkinter-based)
- ⚡ Smart error handling (429, 503)
- 🧠 Feedback logging system

---

## 🛠️ Tech Stack

- Python 🐍  
- Tkinter (GUI)  
- Gemini API (Google AI)  
- dotenv  

---

## 📁 Project Structure

```

Gemini-AI-Assistant/
│
├── scripts/
│   └── app.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md

````

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/gemini-ai-assistant-cli-gui.git
cd gemini-ai-assistant-cli-gui
````

---

### 2️⃣ Create virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Setup API Key

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

---

### 5️⃣ Run the application

```bash
python scripts/app.py
```

---

## ⚠️ Error Handling

* 🔁 Handles **429 (Rate Limit)** with retry logic
* 🚦 Handles **503 (Server Busy)** gracefully
* ⏱️ Implements request delay to prevent API spam

---

## 💡 Future Improvements

* 💬 Chat history (like ChatGPT)
* 🌐 Web version (Streamlit)
* 🎤 Voice assistant
* 🎨 Dark mode UI

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Amit Thakur**

---

## ⭐ Show Some Love

If you like this project, give it a ⭐ on GitHub!

---
