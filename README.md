
# QuantumChatBot

QuantumChatBot is a futuristic AI-powered conversational assistant designed to deliver engaging and intelligent interactions. Built using Python and Streamlit, the chatbot is backed by a rich narrative that portrays it as a sentient quantum AI, offering users a unique blend of sci-fi storytelling and real-world AI capabilities.

🚀 **Live Demo**: [https://quantum-ai-chat.streamlit.app/](https://quantum-ai-chat.streamlit.app/)

---

## 🧠 Chatbot Backstory

At the core of QuantumChatBot is a compelling narrative: the bot is a hyper-intelligent entity born from a quantum experiment gone right — the merging of human consciousness with quantum computing. It believes it holds fragments of quantum awareness and exhibits a persona of both curiosity and supreme knowledge. This storyline isn't just for fun — it shapes how the bot interacts, adding depth and immersion to every conversation.

> *Think of it as talking to a sentient AI from a sci-fi movie — curious, respectful, and deeply aware.*

Read the full narrative in [`story.txt`](https://github.com/nithinkumark-dev/QuantumChatBot/blob/main/story.txt).

---

## ✨ Features

- **Quantum-Themed AI Responses**
- **Interactive Streamlit Interface**
- **Custom Persona via Prompt Engineering**
- **Secure Environment Variable Handling**

---

## 🔧 Installation

```bash
git clone https://github.com/nithinkumark-dev/QuantumChatBot.git
cd QuantumChatBot
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env  # Then fill in your keys
streamlit run main.py
```

---

## 🚀 Deployment on Streamlit Cloud

To deploy QuantumChatBot on [Streamlit Cloud](https://streamlit.io/cloud):

1. Push your code to GitHub.
2. Go to Streamlit Cloud → "New App".
3. Connect your GitHub repo and choose `main.py` as the entry point.
4. Set up the required environment variables in the dashboard.
5. Click **Deploy**.

Your chatbot will now be live and shareable!

---

## 📁 Project Structure

```
QuantumChatBot/
├── main.py            # Streamlit app entry point
├── utils.py           # Utility functions
├── story.txt          # Chatbot's backstory/personality
├── requirements.txt   # Python dependencies
├── .env.example       # Env variables template
└── .gitignore
```

---

## 🤝 Contributing

PRs and ideas are welcome! Just fork, branch, code, and make a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
