# 🧠 Summarize AI

**Summarize AI** is an intelligent and user-friendly audio/video/text summarization desktop tool built using `Python` and `CustomTkinter`.  
It uses **Vosk** (offline) for transcription and **Gemini flash2.0** (online) for accurate summarization and keyword extraction.

<p align="center">
  <img src="assets/image/logo.png" alt="Summarize AI Logo" width="200"/>
</p>

---

## 🚀 Features

- 🎥 Extract audio from video (MP4)
- 🎙️ Transcribe audio files (WAV, MP3)
- 📄 Summarize plain text files
- 🤖 Google Gemini AI-based summary and top 5 keywords
- 🧵 Multithreaded transcription for fast processing
- 💾 Auto-save transcribed text and summary
- 🖼️ Dynamic GUI with processing indicators

---

## 🖥️ UI Screenshots


![Initial](assets/image/Screenshot2025-04-14204425.png) | ![Writing](assets/image/Screenshot(6).png) | 
---

## 🛠️ Requirements

- Python 3.9 or above
- FFmpeg (included as `./ffmpeg.exe`)
- Internet

## 🛠️ Technologies Used

| Technology        | Purpose                               |
|-------------------|----------------------------------------|
| Vosk              | Offline speech-to-text transcription   |
| SpeechRecognition | Online speech transcription (Google)   |
| Gemini Flash 2.0  | AI-powered text summarization          |
| Pydub             | Audio splitting and conversion         |
| PIL               | Image processing for GUI               |
| CustomTkinter     | Modern desktop GUI                     |

---

## 🧹 Real-Life Use Cases

- 🎓 **Students**: Summarize lectures and tutorials
- 🏢 **Professionals**: Get meeting summaries in minutes
- 🎤 **Podcasters & Creators**: Extract key points from content
- 📖 **Readers**: Summarize long documents instantly

---

## 📦 How to Use
```bash
git clone https://github.com/amit-sark/SummarizeAi.git
```bash
cd SummarizeAi
```bash
pip install -r requirements.txt
```
```bash
python main.py
```

---

## 🚀 Hackathon Relevance

**Summarize AI** solves a major real-world problem — **time wastage in content consumption**. By combining speech recognition and GenAI, it delivers smart summaries and saves hours of effort.

---

## 📬 Contact / Credits

Made with ❤️ by [Your Name] – Shivox

---