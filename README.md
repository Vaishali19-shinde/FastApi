# Multi-Modal AI Suite (FastAPI + Gemini 3.1 Flash Lite)

## 1. Key Features
* **AI Text Summarization**: Extract concise, structured insights from lengthy articles, notes, or documentation in seconds.
* **Image Analysis**: Upload visual content to receive detailed descriptions, object detection, or context extraction powered by multimodal AI.
* **Interactive AI Chatbot**: Engaging conversational interface capable of context-aware, real-time responses.
* **Lightning-Fast Inference**: Integrated with **Gemini 3.1 Flash Lite** for optimized latency and high throughput.
* **Modern Web Interface**: Responsive and clean front-end UI built with custom styling for a seamless user experience.

---

## 2. Introduction
This project provides an end-to-end multi-modal AI application powered by **FastAPI** on the backend and **Gemini 3.1 Flash Lite** as the intelligence core. The application offers a lightweight, high-performance web dashboard featuring real-time AI tools including automated text summarization, multi-modal image analysis, and an interactive AI chatbot.

---

## 3. Design & Experience
* **Clean UI Components**: Styled using CSS3 custom properties with flexible layout cards and dedicated input/output regions (`index.html`, `style.css`).
* **Asynchronous Communication**: Uses asynchronous Fetch API requests between the frontend interface and FastAPI endpoints to deliver smooth UI updates without page reloads.
* **Responsive Layout**: Dynamic viewports adapted for both mobile screens and desktop monitors.

---

## 4. Project Structure
```text
FastApi/
│
├── main.py              # FastAPI server script containing routes and Gemini integration
├── static/              # Static frontend assets
│   └── style.css        # CSS stylesheets for modern UI layout
├── templates/           # HTML view templates
│   └── index.html       # Single-page web dashboard user interface
├── requirements.txt     # Python dependencies list
└── README.md            # Project documentation

```
---
## 5. Tech Stack

* **Backend Framework**: FastAPI (Python 3.10+)

* **ASGI Web Server**: Uvicorn

* **AI Model Core**: Google Gemini 3.1 Flash Lite

* **Frontend Markup & Styles**: HTML5, CSS3, JavaScript (ES6+)

* **Environment Management**: python-dotenv

---

## 6. Getting Started
* **Prerequisites**
*Python 3.10 or higher

Google Gemini API Key

* **Installation Setup**
1.  **Clone the repository**:
     git clone [https://github.com/Vaishali19-shinde/FastApi.git](https://github.com/Vaishali19-shinde/FastApi.git)
cd FastApi

2. **Create and activate a virtual environment**:
*  **Linux/macOS**:
   python3 -m venv venv
   source venv/bin/activate

* **Windows**:
   python -m venv venv
   venv\Scripts\activate
  
3. **Install dependencies**:
   pip install -r requirements.txt

4. **Configure Environment Variables:
     Create a .env file in the root directory and add your Gemini API Key**:  

   GEMINI_API_KEY=your_google_gemini_api_key_here

     
