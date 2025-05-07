# AI_Mental_-Health_-Assistant

# 🧠 Mental Health Chatbot with Emotion Detection and ECG Visualization

This project is an AI-powered chatbot that supports *text, **voice, and **video* inputs to assist users with mental health support. It includes:
- Emotion detection from text and video
- ECG-style emotional visualization
- Voice responses using text-to-speech
- Friendly web interface using Gradio

---

## 🚀 Features
- 🎤 *Speech-to-Text* using OpenAI Whisper
- 💬 *AI Chatbot* for compassionate conversation
- 😃 *Emotion Detection* from user messages and videos
- 🫀 *ECG Graph* based on emotional state
- 🔊 *Voice Reply* with Google Text-to-Speech (gTTS)

---

## 🧩 Models Used
- *Speech Recognition*: openai/whisper-base
- *Emotion Detection*: j-hartmann/emotion-english-distilroberta-base  
  *(or use custom fine-tuned model: saha6754/mental_health_finetuned)*
- *Chatbot Response*: (Replace with your model/pipeline if any)

---

## 🛠 Installation

### Step 1: Clone the repository
```bash
git clone https://github.com/yourusername/mental-health-chatbot.git
cd mental-health-chatbot

## 🧩 Install Requirements
pip install -r requirements.txt


## Usage
python app.py 

Dataset Used
Mental Health Counseling Conversations Dataset
https://huggingface.co/datasets/Amod/mental_health_counseling_conversations 
****
