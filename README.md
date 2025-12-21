# SpeechTrans 
SpeechTrans is an AI-based speech translation system that automatically converts English audio/video into natural Hindi speech.
It is designed for dubbing, accessibility, and cross-language communication.

         🚀 Features

🗣️ Speech Recognition – Converts English speech to text

🌐 Translation – Translates text into Hindi using ML models

🔊 Speech Synthesis – Generates natural Hindi audio output

🎬 Video Dubbing – Can be used to dub English videos into Hindi

🤖 Built with Python, NLP, and ML pipelines

# Speech Trans — Streamlit app

Two modes:
- Local (offline) using OpenAI `whisper` model (requires ffmpeg & CPU resources)
- Cloud (recommended for Streamlit Cloud) using OpenAI Speech-to-Text API (requires OPENAI_API_KEY)

## Files
- `streamlit_app.py` — Streamlit UI
- `transcriber.py` — backend wrapper (local or OpenAI)
- `requirements.txt`

## Run locally (VS Code)
1. Clone repo and open in VS Code.
2. Create venv:
   ```bash
   python -m venv venv
   source venv/bin/activate     # mac/linux
   venv\Scripts\activate        # windows

