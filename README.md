# 🗣️ Kinyarwanda Voice Companion

A lightweight, AI-powered voice assistant built specifically for Kinyarwanda speakers. This tool enables seamless voice interaction by converting spoken language into text, understanding the query, and responding with lifelike speech.

---

## 🚀 What This Project Does

This assistant is designed to support **end-to-end voice communication** in Kinyarwanda. The system enables you to:

- 🎙️ Speak naturally in Kinyarwanda
- 🧠 Get meaningful responses via AI or rule-based logic
- 🔊 Hear back clear Kinyarwanda speech in real-time

Whether you're building a localized chatbot, learning language tech, or experimenting with voice AI, this project serves as a flexible foundation.

---

## ✨ Key Capabilities

| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 🎧 Voice Recognition | Translates Kinyarwanda speech into text using pre-trained acoustic models   |
| 🤖 NLP Engine        | Understands the user's intent using hybrid logic (rule-based + GPT)         |
| 🔈 Voice Synthesis   | Responds in fluent, natural Kinyarwanda using TTS technology                |
| 🌐 Web Interface     | Launches an interactive UI powered by Gradio                                |
| 💬 Custom Responses  | Supports intent-specific, predefined answers for faster interaction         |

---

## 🧠 How It Works

graph TD
A[🎙️ User Speaks] --> B[STT Engine - Transcribe Speech]
B --> C[NLP Module - Understand Intent]
C --> D[Response Generation - Rule or GPT]
D --> E[TTS Engine - Synthesize Speech]
E --> F[🔊 Audio Output]
🛠 Installation Guide
⚙️ Requirements
Python 3.8 or later

GPU (for TTS performance, optional)

pip

🔧 Setup Steps
bash
Copy
Edit
# Clone your version
git clone https://github.com/YOUR_USERNAME/kinyarwanda-voice-companion.git
cd kinyarwanda-voice-companion

# Install dependencies
pip install -r requirements.txt
Ensure any model dependencies (STT or TTS) are downloaded or mounted via Google Drive.

📸 Screenshots
Replace or add your own screenshots under the assets/ folder.

Gradio Web UI

Terminal Interaction

🧪 Running the Assistant
Local Run
bash
Copy
Edit
python kin_assistant.py
Google Colab
Open kin_assistant.ipynb

Mount your Google Drive with model files

Run all cells and launch the interface

🧰 Technology Stack
STT: NeMo-based Kinyarwanda model

TTS: MB-iSTFT-VITS2 via KinyaTTS

NLP: Rule-based intent matcher + GPT fallback

UI: Gradio for interactive experience

❗ Known Issues
Background noise can reduce recognition accuracy

Occasionally confuses similar-sounding languages (e.g., Kiswahili)

Large models may require Google Colab or GPU for smooth inference

📁 Resources
📓 Notebook: kin_assistant.ipynb

🧠 TTS Model: KinyaTTS Inference

🗣️ STT Model: RW-DEEPSPEECH-API

🧑‍💻 Author
This version is maintained and adapted by Dieudonne. Original ideas have been extended and restructured for educational and experimental purposes in the field of voice AI for African languages.

📄 License
This project is distributed under the MIT License. Feel free to modify, distribute, or build upon it.
