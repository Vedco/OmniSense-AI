# OmniSense-AI (Text + Image + Audio + Video)
An AI-powered multimodal assistant enabling real-time text, voice, image, and video understanding.

An advanced Multimodal AI Assistant capable of understanding and responding to multiple input formats including text, speech, images, and videos using modern Generative AI models.

This project demonstrates applied AI engineering by integrating speech recognition, computer vision, large language models (LLMs), and text-to-speech systems into a unified intelligent assistant.

---

## 🌟 Features

- ✅ Text-based AI conversations
- ✅ Voice input (Speech-to-Text)
- ✅ Text-to-Speech responses
- ✅ Image understanding & visual reasoning
- ✅ Video summarization
- ✅ Modular architecture
- ✅ Real-time multimodal interaction

---

## 🧠 How It Works

The assistant follows a multimodal processing pipeline:

### 1️⃣ Input Layer
- Text input
- Voice input (microphone/audio file)
- Image upload
- Video upload

### 2️⃣ Preprocessing Layer
- Speech converted to text
- Images processed using vision models
- Video frames extracted & analyzed

### 3️⃣ AI Processing Layer
- Processed input sent to LLM (Gemini / GPT APIs)
- Model generates contextual response

### 4️⃣ Output Layer
- Text response displayed
- Optional speech output using Text-to-Speech (gTTS)

---

## 🏗 Project Architecture

```
User Input
   ↓
Input Handler (Text / Audio / Image / Video)
   ↓
Preprocessing (STT / Vision / Frame Extraction)
   ↓
LLM Processing
   ↓
Response Generation
   ↓
Text Output + Optional Speech Output
```

---

## 📂 Project Structure

```
Multimodal-AI-Assistant/
│
├── app.py                    # Main application controller
├── audio_handler.py          # Handles audio file processing
├── image_handler.py          # Handles image processing
├── video_handler.py          # Handles video analysis
├── voice_input.py            # Microphone input handling
├── text_to_speech_gTTS.py    # Converts text responses to speech
├── helper.py                 # Utility functions
├── handlers_imports.py       # Centralized imports
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```

---

## 🛠 Tech Stack

- Python
- Generative AI APIs (Gemini / GPT)
- SpeechRecognition
- gTTS (Text-to-Speech)
- OpenCV
- PIL
- Streamlit / UI framework

---

## 🔧 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/multimodal-ai-assistant.git
cd multimodal-ai-assistant
```

### 2️⃣ Create virtual environment
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the application
```bash
python app.py
```

---

## 🎯 Example Use Cases

- AI-powered learning assistant
- Smart document summarizer
- Visual content analyzer
- Voice-enabled chatbot
- Video summarization tool

---

## 🚀 Future Enhancements

- Add Retrieval-Augmented Generation (RAG)
- Implement conversation memory
- Convert to FastAPI backend
- Docker containerization
- Cloud deployment (AWS / GCP)
- Add real-time streaming responses

---

## 📈 Skills Demonstrated

- Multimodal AI system design
- Large Language Model integration
- Speech-to-Text and Text-to-Speech pipelines
- Computer Vision + NLP integration
- Modular software architecture
- End-to-end AI application development

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Ved Bhatt  
Master’s in Data Science (AI Focus)

