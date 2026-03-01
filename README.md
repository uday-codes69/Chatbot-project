# 🧠 Groq AI Intelligence - Advanced Chatbot

![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-1.30+-FF4B4B.svg)
![Groq](https://img.shields.io/badge/Groq-Llama3-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

An ultrafast, high-performance AI chatbot built with **Streamlit** and powered by the **Groq LPU™ Inference Engine**. Experience sub-second tokens-per-second responses with state-of-the-art LLMs like Llama 3.3 and Mixtral.

---

## ✨ Features

- 🏎️ **Extreme Speed**: Powered by Groq's LPU for near-instantaneous inference.
- 💬 **Full Conversation Memory**: Maintains context throughout the chat session.
- 🌊 **Real-time Streaming**: Watch the AI "think" and "type" with smooth streaming delta updates.
- 🛠️ **Configurable Settings**: Toggle between models (Llama 3.3, Mixtral, Gemma) and adjust temperature/max tokens on the fly.
- 🌑 **Premium Dark UI**: A refined, modern aesthetic designed for readability and focus.

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/uday-codes69/Chatbot-project.git
cd Chatbot-project
```

### 2. Set up environment variables
Create a `.env` file in the root directory and add your Groq API Key:
```env
GROQ_API_KEY=your_api_key_here
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch the App
```bash
streamlit run app.py
```

---

## 🛠️ Technology Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **LLM API**: [Groq Cloud SDK](https://console.groq.com/)
- **Environment Management**: `python-dotenv`
- **Logic**: Python 3.x

---

## 📂 Project Structure

- `app.py`: The main Streamlit interface and UI logic.
- `llm.py`: Backend wrapper for the Groq API handling streaming and logic.
- `requirements.txt`: List of necessary Python packages.
- `.env`: (Private) Storage for your API credentials.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have ideas for new features or improvements.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Built with ❤️ by [uday-codes69](https://github.com/uday-codes69)
