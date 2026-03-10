# 🧭 Quest AI

Quest AI is an interactive AI-powered storytelling platform where users create adventures by selecting choices that shape the narrative. The AI dynamically generates story progressions based on user decisions, creating unique and engaging adventure experiences.

---

# 🚀 Features

- 🧠 AI-generated storytelling
- 🎮 Choice-based adventure progression
- 🌍 Unique story paths for every session
- ⚡ Fast and interactive web interface
- 🏗 Modular backend and frontend architecture

---

# 🏗 Project Structure


Quest-AI
│
├── backend
│ ├── core
│ ├── routers
│ ├── schemas
│ ├── init.py
│ ├── main.py
│ ├── database.db
│ ├── requirements.txt
│ ├── pyproject.toml
│ └── README.md
│
├── frontend
│ ├── public
│ ├── src
│ ├── index.html
│ ├── package.json
│ ├── package-lock.json
│ ├── vite.config.js
│ └── README.md
│
├── LICENSE
└── README.md


---

# ⚙️ Technology Stack

## Backend
- **Python**
- **FastAPI**
- **SQLite**
- **Groq API / LLM integration**

## Frontend
- **React**
- **Vite**
- **JavaScript**
- **HTML/CSS**

---

# 🧠 How Quest AI Works

1. The user starts the adventure.
2. The AI generates a story scenario.
3. The user selects options to guide the story.
4. The AI processes the choice and generates the next part of the narrative.
5. The adventure evolves dynamically based on user decisions.

Every playthrough can produce a different story path.

---

# 🛠 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/quest-ai.git
cd quest-ai

### Install dependencies
```bash
cd backend
pip install -r requirements.txt