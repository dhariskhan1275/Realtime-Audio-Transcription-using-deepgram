# 🎤 Real-Time Speech-to-Text using Deepgram API

## 🚀 Overview
This Python project captures audio from your microphone and streams it to Deepgram's API for real-time transcription. 📝 The transcribed text is then displayed on the console.

## 🔧 Features
✅ **Real-time speech-to-text conversion** using Deepgram's API  
✅ **Microphone streaming** with PyAudio  
✅ **Asynchronous processing** for smooth performance  
✅ **Stop listening feature** (say *"stop listening"* to end the transcription)  
✅ **Error handling** for stable execution  

---

## 📌 Installation

Ensure you have Python installed (version 3.7+ recommended). Then, install the required dependencies:

```bash
pip install pyaudio websockets python-dotenv
```

For Linux users, you might need to install PyAudio manually:
```bash
sudo apt-get install portaudio19-dev
pip install pyaudio
```

---

## 🛠 Setup

1️⃣ Create a `.env` file in the project directory and add your Deepgram API key:
```env
DEEPGRAM_API_KEY=your_api_key_here
```

2️⃣ Run the script:
```bash
python your_script.py
```

---

## 🎙 How It Works
1️⃣ **Opens a WebSocket connection** to Deepgram’s API ✅  
2️⃣ **Captures microphone audio** and streams it in real-time 🎤  
3️⃣ **Displays transcriptions** on the console 📄  
4️⃣ **Say “stop listening”** to end the session ⏹

---

## 🔍 Command-Line Arguments
You can customize the model, tier, and API host:

```bash
python your_script.py --model enhanced --tier base
```

| Argument       | Description | Default |
|---------------|-------------|---------|
| `--model` | Deepgram model (e.g., `general`, `enhanced`) | `general` |
| `--tier` | Deepgram tier (`base`, `enhanced`) | `""` |
| `--host` | Deepgram API WebSocket URL | `wss://api.deepgram.com` |

---

## ⚠️ Error Handling
- **Missing API Key?** Ensure `.env` contains `DEEPGRAM_API_KEY`.
- **Connection Issues?** Check your internet and Deepgram service status.
- **Invalid API Key?** Verify your Deepgram account credentials.

---

## 📜 License
This project is **open-source** and available under the MIT License. 🛠

---

## 📞 Contact
For any issues, feel free to reach out! 🚀

💻 Developed by **Muhammad Haris** 🎯  
📧 dhariskhan1275@gmail.com ✉️  
🔗https://www.linkedin.com/in/muhammad-haris-681958239/
