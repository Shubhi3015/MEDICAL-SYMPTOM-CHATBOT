# 🩺 AI-Powered Medical Symptom Checker Chatbot 🤖

An intelligent chatbot built using **Python**, **Gradio**, and **Gemini 2.5 Flash API** that provides **general medical guidance** based on symptoms described by users through **text or speech input**.

---

## 🚀 Features

- 💬 **Natural Language Symptom Input**  
  Users can describe symptoms via **text** or **voice**, powered by the `speech_recognition` library.

- 🔊 **Text-to-Speech Output**  
  Responses are read out loud using `pyttsx3` for a conversational experience.

- 🧠 **LLM Integration with Gemini API (2.5 Flash)**  
  Uses custom prompts and context handling for better health-related responses.

- 🌐 **User-Friendly Gradio Interface**  
  Clean and responsive frontend for typing, speaking, and listening to replies.

- ⚠️ **Disclaimer**  
  *This tool does not provide professional medical advice. It is for informational purposes only.*

---

## 🛠️ Tech Stack

- **Python 3.10+**
- [Gradio](https://gradio.app/)
- [Gemini 2.5 Flash API](https://ai.google.dev/)
- `pyttsx3` (TTS)
- `speech_recognition` (STT)
- Custom prompt logic with contextual memory

---

## 📸 Screenshots

> ![UI Screenshot 1](screenshots/screenshot1.png)  
> ![Voice Interaction](screenshots/screenshot2.png)  
> ![Gemini Response](screenshots/screenshot3.png)

---

## 🏁 How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/yourusername/medical-symptom-checker-chatbot.git
   cd medical-symptom-checker-chatbot
