# ⚡ Gemini AI Studio — Multimodal Intelligence Suite

An interactive, full-stack AI web application powered by **FastAPI** and **Google Gemini (`gemini-3.1-flash-lite`)**. The application offers a modern AI studio experience featuring neural text summarization, multimodal image vision analysis, and a contextual QA chatbot with a glassmorphic UI.

---

## ✨ Key Features

### 1. 📄 Neural Text Summarizer
* 🧠 **Intelligent Synthesis**: Condense lengthy articles, meeting transcripts, or research papers into concise key takeaways.
* 📊 **Real-Time Text Metrics**: Live word count, character count, and estimated reading time calculations.
* 📉 **Reduction Badge**: Instant display of compression ratio (e.g., 📉 68% condensed).
* ⚡ **Quick Presets**: 1-click preset topics (Quantum Computing, Renewable Energy, Artificial Intelligence).
* 🔊 **Audio & Export**:
  * 🗣️ **Read Aloud**: Listen to summaries using the browser's native SpeechSynthesis Web Speech API.
  * 📋 **Copy to Clipboard**: Instant copy with visual feedback and toast notifications.
* ⌨️ **Keyboard Shortcut**: `Ctrl + Enter` (or `Cmd + Enter`) to trigger summarization immediately.

### 2. 📸 Image Vision Studio
* 👁️ **Multimodal Context Inspection**: Upload images, diagrams, architectural charts, or screenshots for detailed visual analysis.
* 📥 **Drag & Drop Zone**: Drag files directly into the dropzone or paste images straight from clipboard (`Ctrl + V`).
* 🔍 **Live Preview & Metadata**: Real-time image rendering, filename display, file size badge, and an instant removal button.
* 🎯 **High-Tech Laser Scanner**: Animated scanning laser effect across the image container during active processing.
* 🎨 **Preset Canvas Generators**: Built-in 1-click test graphics (*Neural Network Topology* and *Growth Trend Chart*).

### 3. 🤖 Intelligent Chatbot (QA)
* 💬 **Conversational Interface**: Modern message bubbles with distinct user/AI avatars, timestamps, and formatted markdown output.
* ⏳ **Typing Indicator**: Animated 3-dot thinking pulse while awaiting backend responses.
* 🚀 **Quick Starters**: Curated sample prompts to jumpstart conversations.
* 🛠️ **Message Tools**: Individual copy and read-aloud buttons attached to every AI response.
* 💾 **Export & Reset**:
  * 📝 **Export to Markdown**: Download full conversation history as a formatted `.md` file.
  * 🧹 **Reset**: Clear conversation state and chat history with a single click.

### 4. 🎨 Design & Experience
* 🌌 **Futuristic AI Studio Aesthetics**: Curated dark and light themes with glowing ambient radial mesh orbs.
* 💎 **Glassmorphism**: Translucent frosted-glass cards with subtle borders (`backdrop-filter: blur(20px)`).
* 🔔 **Web Audio API Chimes**: Gentle synthesized audio feedback chimes for user actions without external sound assets.
* 📡 **Live Health Status & Demo Mode**:
  * Pings the FastAPI backend every 15 seconds to display real-time connection health (🟢 Online / 🟡 Offline).
  * Built-in interactive **Demo Mode** allows testing UI flows, animations, and simulated responses even when offline.
  * Custom API URL configuration modal.

---

## 📌 Introduction

**Gemini AI Studio** bridges cutting-edge generative AI models with a sleek, user-centric interface. Built on top of **FastAPI** for high-throughput asynchronous execution and **Gemini 3.1 Flash Lite** for ultra-fast multi-modal responses, this suite provides a turnkey solution for developers and end-users seeking real-time text summarization, image vision analysis, and contextual chat interactions in a single web dashboard.

---

## 🌟 Design & Experience Overview

The interface is engineered with modern frontend design principles:
* ⚡ **Asynchronous Fetch Flow**: Non-blocking asynchronous API requests ensure smooth UI updates without full page reloads.
* 📱 **Responsive Layout**: Designed dynamically with CSS grid/flexbox to accommodate wide desktop monitors, tablets, and mobile screens seamlessly.
* 🔊 **Accessibility & Feedback**: Audio-visual cues, toast notifications, keyboard shortcuts, and smooth transitions enhance overall usability.

---

## 📁 Project Structure

```text
FastApi/
│
├── main.py              # FastAPI server containing routes, CORS, and Gemini endpoints
├── static/              # Static frontend resources
│   └── style.css        # Glassmorphism CSS design system & custom animations
├── templates/           # Frontend view templates
│   └── index.html       # Single-page web application interface
├── requirements.txt     # Python dependencies list
└── README.md            # Project documentation
