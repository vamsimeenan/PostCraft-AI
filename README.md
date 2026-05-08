# 📝 PostCraft AI

> **Intelligent AI-Powered LinkedIn Post Generation Platform** — Create engaging, professional LinkedIn posts instantly using Few-Shot Prompt Engineering.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-0.1+-green?style=for-the-badge&logo=chainlink&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red?style=for-the-badge&logo=streamlit&logoColor=white) ![Groq](https://img.shields.io/badge/Groq_API-Enabled-orange?style=for-the-badge) ![Llama](https://img.shields.io/badge/Llama_3.2-Meta-blueviolet?style=for-the-badge)

---

## 📌 Overview

**PostCraft AI** takes the friction out of LinkedIn content creation. Using **Llama 3.2**, **LangChain**, **Groq API**, and **Few-Shot Prompt Engineering**, it generates personalized, style-aware LinkedIn posts in seconds — replicating your tone, structure, and voice through a clean Streamlit interface.

Maintaining a consistent LinkedIn presence is time-consuming, repetitive, and hard to scale. PostCraft AI solves all of that.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 AI Post Generation | High-quality LinkedIn posts via Llama 3.2 |
| 🎭 Style Replication | Mimics your writing tone using few-shot learning |
| ⚡ Fast Inference | Ultra-low latency powered by Groq API |
| 🧠 Prompt Engineering | Optimized prompts for consistent, quality output |
| 📌 Topic-Aware Content | Tailored to your chosen topic, tone, and length |
| 🎨 Clean UI | Responsive and intuitive Streamlit interface |

---

## 🏗️ Architecture
User Input → Streamlit UI → Prompt Engineering → Few-Shot Learning
→ LangChain Pipeline → Groq API + Llama 3.2 → LinkedIn Post Output
---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| Python | Core Backend |
| LangChain | LLM Orchestration |
| Groq API | Fast AI Inference |
| Llama 3.2 | Content Generation |
| Streamlit | Frontend UI |
| Few-Shot Prompting | Style Personalization |

---

## 📂 Structure
PostCraft-AI/
├── app.py
├── chains/
├── prompts/
├── few_shot_examples/
├── assets/
├── requirements.txt
├── .env
└── README.md
---

## 🚀 Quick Start

```bash
# 1. Clone
git clone https://github.com/vamsimeenan/PostCraft-AI.git
cd PostCraft-AI

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
# venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment
echo "GROQ_API_KEY=your_api_key_here" > .env

# 5. Run
streamlit run app.py
```

---

## 🎯 Impact

> 🚀 Reduces LinkedIn content creation time by up to **80%** using AI automation.

- Maintain consistent posting schedules
- Strengthen your professional brand
- Generate content faster without quality loss
- Scale outreach without scaling effort

---

## 🔮 Roadmap

- [ ] Multi-platform content generation (Twitter/X, Instagram)
- [ ] AI hashtag & engagement optimization
- [ ] LinkedIn direct publishing integration
- [ ] User auth & content history
- [ ] Multi-language support
- [ ] Fine-tuned personalization models

---

## 👨‍💻 Author

**Vamsi Meenan Ravuri** — AI • Full Stack • Software Engineering

[![GitHub](https://img.shields.io/badge/GitHub-vamsimeenan-black?style=flat&logo=github)](https://github.com/vamsimeenan)

---

## 🤝 Contributing

Fork → create a branch → commit → open a Pull Request. All contributions welcome!

---

⭐ **Star** the repo if it helped • 🍴 **Fork** and build on it • 📜 Educational use license

*Built to make LinkedIn less of a chore and more of a superpower. 🚀*

