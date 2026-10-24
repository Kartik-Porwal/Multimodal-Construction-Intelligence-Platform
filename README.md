# 🏗️ Multimodal Construction Intelligence Platform

**Skill Wallet Capstone Project 1**

An AI-powered, production-ready Streamlit application for construction site intelligence — integrating Google Gemini multimodal AI for safety auditing, structural diagnostics, real-estate valuation, and an intelligent site assistant.

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 🦺 **Site Safety & PPE Audit** | Upload construction site photos → AI analyzes PPE compliance (helmets, vests, boots, harness) under OSHA 1926 & IS 456 standards → Structured JSON report with safety score, hazard list, and corrective remedies |
| 🔍 **Crack Diagnostics** | Upload concrete/wall defect images → AI classifies defect type, estimates crack width, identifies root causes, and recommends engineering repairs with urgency levels |
| 📊 **Planning & Valuation** | Interactive project configurator → Budget, CapEx, market valuation in INR, steel/cement estimates, milestone progress, and AI-generated 3D architectural render via Pollinations |
| 🤖 **Site Assistant** | Weather-aware safety advisory system + multi-turn construction engineering chatbot powered by Gemini |

## 🚀 Quick Start

```bash
# Clone & navigate
cd "Multimodal Construction Intelligence Platform"

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## 🔑 API Key

1. Get a free **Google Gemini API key** from [AI Studio](https://aistudio.google.com/app/apikey)
2. Enter it in the sidebar when the app launches
3. Without a key, the app runs in **Demo Mode** with realistic sample data

## 📁 Project Structure

```
├── app.py              # Main Streamlit application (entry point)
├── gemini_client.py    # Gemini API wrapper + demo fallback data
├── prompts.py          # All AI prompt templates
├── styles.py           # Premium CSS design system
├── requirements.txt    # Python dependencies
├── .streamlit/
│   └── config.toml     # Streamlit theme & server config
└── README.md
```

## 🌐 Deploy to Streamlit Cloud

1. Push this repo to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Select your repo → Set main file to `app.py`
4. Deploy — zero database dependencies, works out of the box ✅

## 🛠️ Tech Stack

- **Frontend:** Streamlit with custom CSS design system
- **AI Engine:** Google Gemini 1.5 Flash (multimodal)
- **Image Gen:** Pollinations AI (3D architectural renders)
- **Standards:** OSHA 1926, IS 456:2000, IS 13920, NBC India 2016

---

Built with ❤️ for the Skill Wallet Capstone Program
