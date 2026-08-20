# 👁️ Gemini Vision - Smart Camera AI

A lightweight, Progressive Web App (PWA) that turns your browser into an intelligent vision assistant powered by the Google Gemini API. It analyzes live camera feeds, detects objects with bounding boxes, reads text (OCR), answers voice/text questions, and speaks responses aloud.

---

## ✨ Features

- **Live Vision Analysis**: Scan objects, text, scenes, and food in real time.
- **2D Bounding Boxes**: Automatically overlays detected objects directly on the camera feed.
- **Multimodal Interaction**:
  - **Text Input**: Type questions about the visible scene.
  - **Voice Input (STT)**: Ask questions hands-free via Web Speech Recognition.
  - **Text-to-Speech (TTS)**: Natural voice narration for analysis results.
- **Scanning Modes**:
  - 🔍 **Object Detect**: Detect and pinpoint items in view.
  - 📄 **OCR**: Read and extract text, signs, labels, or numbers.
  - 🌟 **Scene Detail**: Analyze scene context and ambient surroundings.
  - 🥗 **Food & Nutrition**: Identify dishes and estimate nutritional details.
- **Continuous Auto-Scan**: Automated periodic scanning mode for hands-free observation.
- **Hardware Controls**: Torch/flashlight toggle, digital zoom (1x, 2x, 3x), and front/rear camera flip.
- **Customizable AI**: Adjust AI personality (assistant, humorous, detective, teacher, poetic) and temperature.
- **Bilingual Support**: Instant toggle between Indonesian (ID) and English (EN).
- **PWA & Mobile Ready**: Standalone display support, offline caching via Service Worker, and responsive mobile-first UI.

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser with camera and microphone permissions enabled (Chrome, Edge, Safari).
- A **Google AI Studio API Key** ([Get one here](https://aistudio.google.com/)).

### Running the App

1. Clone or download the repository containing `index.html`.
2. Open `http://your_computer/index.html` (or your server's URL) in your browser.
3. On first launch, open **Settings (⚙️)**, paste your **Gemini API Key**, and click **Save & Start**.

---

## 🛠️ Configuration

Open the **Settings** modal in the top-right corner to customize:
- **API Key**: Your Google Gemini API key.
- **Model**: Default is `gemini-3.5-flash-lite` (can be configured to other Gemini multimodal models).
- **Temperature**: Controls creativity/randomness (0.0 to 1.0).
- **AI Personality**: Sets system behavior (Smart Assistant, Humorous, Detective, Teacher, Poetic).

---

## 🔒 Privacy & Permissions

- **Camera & Mic**: Frames and audio transcripts are processed on-demand and sent directly from your browser to the Google Gemini API.
- **API Key**: Stored securely in your browser's `localStorage` and never transmitted to third-party servers.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
