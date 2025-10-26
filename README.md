# LinguaCap

**Understand any video, in any language — live.**

LinguaCap is a Chrome extension that listens to the audio of any tab (e.g., YouTube, Dailymotion) and generates real-time subtitles using AI speech recognition and translation.

## 🚀 Problem

Ever watched a video with no subtitles or in another language?
Existing tools either require you to find `.srt` files or rely on limited site support. 
LinguaCap solves this by adding *live AI-powered subtitles* directly in your browser.

## ⚙️ How It Works
1. Capture tab audio using Chrome’s tabCapture API.
2. Stream audio to an AI Speech-to-Text engine (OpenAI Whisper / Deepgram).
3. Translate text to your target language.
4. Overlay live captions directly on the video.

## 🧩 Tech Stack
- **Frontend:** Vanilla JS + HTML + CSS (Chrome Extension)
- **Backend (optional):** Node.js for API key protection and WebSocket streaming
- **AI APIs:** 
  - Whisper API (Speech-to-Text)
  - Google Translate API (Translation)

## 🛠️ Current MVP Goals
- [ ] Capture tab audio and chunk it in real-time
- [ ] Send to Whisper API and get transcripts
- [ ] Display subtitles overlay on active tab
- [ ] Translate to English
- [ ] Basic styling + on/off controls

## 🔮 Future Roadmap
- Multi-language support
- Offline transcription (Whisper Tiny WASM)
- Custom subtitle styling
- Save subtitles as `.srt`
- Freemium monetization model

## 📜 License
MIT License

---

*Built by Nidhi — solving real problems with real code.*
