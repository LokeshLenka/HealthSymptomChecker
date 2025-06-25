# 🩺 AI Medical Symptom Checker

A minimalist AI-powered web app that analyzes user symptoms and provides preliminary medical insights using **DeepSeek R1 via OpenRouter**.

> ⚠️ **Disclaimer:** This tool is for informational purposes only and does **not** replace professional medical advice. Always consult with a healthcare provider.

---

## 🚀 Features

- ✅ Add, remove, and customize symptoms
- ✅ Tracks patient age and gender
- ✅ Real-time AI symptom analysis using DeepSeek R1
- ✅ Responses categorized as **Urgent**, **Monitor**, or **Routine**
- ✅ Saves symptom data locally (via `localStorage`)
- ✅ Fully offline-friendly UI — no backend required
- ✅ OpenRouter API integration (secure .env key usage)

---

## 🛠 Tech Stack

- [React](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/) for fast builds
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [OpenRouter](https://openrouter.ai/) for LLM access (DeepSeek R1)
- No database or server — all data lives in the browser

---

## 🧪 Live Demo
---
https://healthsymptomchecker.onrender.com
---

## 📦 Setup

### 1. Clone the project

```bash
git clone https://github.com/your-username/ai-symptom-checker.git
cd ai-symptom-checker
```
### 2. Install the npm

```bash
npm install
npm run dev
