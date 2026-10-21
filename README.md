# 🎧 KathaVoice — Sacred Shloka & Book Explainer

> **Hear sacred shlokas read aloud, then explained in your mother tongue — like a wise elder sitting beside you.**

[![Live Demo](https://img.shields.io/badge/Live_App-https%3A%2F%2Fstoryvoice--d7219.web.app-amber?style=for-the-badge&logo=firebase)](https://storyvoice-d7219.web.app)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable_on_All_OS-emerald?style=for-the-badge)](https://storyvoice-d7219.web.app)
[![Languages](https://img.shields.io/badge/Languages-9_Indian_Languages-orange?style=for-the-badge)](#supported-languages)

---

## 🌟 What is KathaVoice?

Most people want to understand scriptures like the **Bhagavad Gita, Upanishads, and ancient wisdom**, but ancient texts can feel daunting or robotic when translated literally.

**KathaVoice** bridges this gap:
1. **Reads every verse** in its sacred, original text (Sanskrit, Hindi, Kannada, etc.).
2. **Explains every line thoroughly** like a loving grandparent or village Katha Vachak in your mother tongue.
3. **Installs instantly on any device** (Android, Windows, Mac, iPhone) directly from the web link as a Progressive Web App (PWA).

---

## 🚀 Key Features

- **🎧 Two Experience Modes**:
  - `✨ Katha Only (Default)`: Pure, fluent mother-tongue storytelling that explains every line without awkward robotic chanting.
  - `📜 Shloka First + Katha`: Meditative recitation followed by the complete deep explanation.
- **📖 Complete Line-by-Line Explanation**: Instructs AI to never skip a single verse or idea on the page.
- **✨ Sign & Symbol Sanitization**: Automatically strips quotation marks, pipes, and formatting so the audio voice speaks cleanly and naturally without reciting punctuation names.
- **📱 Universal Multi-OS PWA**:
  - 1-tap install on **Android** (Google Chrome, Edge, Samsung Internet).
  - Native window on **Windows PC & Mac**.
  - Guided 2-step **"Add to Home Screen"** on **iPhone & iPad** (iOS Safari).
- **🎙️ 4 Real Human Storytelling Styles**:
  - 🌿 *Wise Elder (Naani/Thatha)* — Warm, patient life truths.
  - 🔥 *Katha Vachak* — Spiritual passion and village stage energy.
  - ☕ *Chai with a Friend* — Casual, relatable conversation.
  - 🧘 *Zen Philosopher* — Serene, quiet reflection.

---

## 🌐 Supported Languages

| Language | Native Script | Voice Engine |
|---|---|---|
| **English** | Latin | Indian English Storyteller |
| **Kannada (ಕನ್ನಡ)** | ಕನ್ನಡ | ಸಹಜ ಕಥಾ ಶೈಲಿ |
| **Hindi (हिन्दी)** | हिन्दी | दिल की बात |
| **Telugu (తెలుగు)** | తెలుగు | హృదయపూర్వక కథనం |
| **Tamil (தமிழ்)** | தமிழ் | இதயம் தொடும் கதை |
| **Marathi (मराठी)** | मराठी | रसाळ जीवन कथन |
| **Bengali (বাংলা)** | বাংলা | হৃদয়গ্রাহী গল্পকথন |
| **Gujarati (ગુજરાતી)** | ગુજરાતી | સહૃદય વાર્તા |
| **Malayalam (മലയാളം)** | മലയാളം | ഹൃദ്യമായ കഥ |

---

## 🤝 What Do Contributors Do on GitHub?

When you list a project on GitHub, **contributors** are developers, translators, designers, and testers from all over the world who help improve your app:

1. **Add More Indian Languages & Dialects**: Contributors fluent in regional languages (Odia, Punjabi, Assamese, Tulu, Maithili) can add new voices and tone styles.
2. **Improve Pronunciation & Scripts**: Scholars and linguists can contribute phonetic sandhi-splitting rules so Sanskrit and Vedic chants sound even more authentic.
3. **Enhance UI & Animations**: Frontend developers can design smoother audio visualizers, dark/temple themes, and responsive layouts.
4. **Fix Bugs & Test Devices**: Testers can report issues across different Android phones, iPhones, iPads, and Mac/Windows setups.
5. **You Remain in Full Control**: As the repository owner, you review every Pull Request (PR) and decide whether to approve (`Merge`) or reject any contribution.

---

## 💻 Tech Stack

- **Frontend**: Vanilla HTML5, TailwindCSS, Web Speech API, PDF.js, Mammoth.js.
- **AI Engine**: Google Gemini Multimodal API (supports image scanning of printed scripture books and PDF pages).
- **Audio TTS**: Google Cloud TTS with fallback to Web Speech Synthesis.
- **Hosting & PWA**: Firebase Hosting, Service Worker cache, Web App Manifest.

---

## 📲 How to Install & Run Locally

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/kathavoice.git

# Navigate to the folder
cd kathavoice

# Serve locally using any local web server
npx serve .
# Or Python
python -m http.server 8080
```

---

## 📜 License

MIT License — Feel free to contribute, share, and spread sacred wisdom!
