# Titans-Tech
<b>MindMitra – Tech Stack & Architecture</b>

## Current Tech Stack:

### 1. Frontend (Web App)
<ul>
<li>React.js – For creating fast, interactive UI.</li>
<li>HTML, CSS, JavaScript – Structure and styling.</li>
<li>Framer Motion / GSAP – For smooth animations.</li>
<li>React Router – For routing between home and chatbot pages.</li>
</ul>


### 2. Backend
<ul>
<li>Flask (Python) – Lightweight backend framework to manage API requests and serve ML model predictions.</li>
<li>DialoGPT – A fine-tuned transformer-based model from Microsoft, used for conversational dialogue.</li>
<li>MindBERT – A BERT-based custom model trained for emotion classification and intent detection.</li>
</ul>

### 3. Database
<ul>
<li><b>MongoDB (NoSQL)</b> – To store user data, conversation logs, emotion records, etc.</li>
</ul>


### 4. Voice & Language Tools
<ul>
<li><b>SpeechRecognition</b> (Python Library) – For converting voice input to text.
gTTS / <b>ResponsiveVoice / Web Speech API</b> – For converting bot’s response back to voice.
Google Translate API – For <b>multilingual support</b> (Hindi, English, French, etc.)</li>
</ul>


---

## What Makes MindMitra Unique (Compared to Others)
<b>Emotion Detection using MindBERT</b> to personalize replies.
<b>Multilingual and Voice Enabled Chatbot.</b>
Completely Offline ML Model (DialoGPT + MindBERT), no dependence on OpenAI’s paid API.
Future Vision for Community & SOS, making it more than just a chatbot—<b><i>a mental health ecosystem.</i></b>


---

## Future Features & Tech Stack

### 1. SOS System (Crisis Detection & Emergency Support)

<i><b>Goal:</b></i>
To automatically detect if a user is showing suicidal, harmful, or highly distressed behavior based on:
Conversation patterns
Emotion scores
Time spent and frequency
Tech Stack:

### 2. Community Feature (User-to-User Interaction & Forums)

<i><b>Goal:</b></i>
Allow users to join mental health communities, share experiences, and support one another anonymously.
Tech Stack:


---

## Planned Integration of ChatGPT API (OpenAI)

<b>Currently:</b>
MindMitra is using <b>DialoGPT</b> locally, which is cost-effective and controllable.


# Future Plan:

<b>Integrate OpenAI’s ChatGPT API for:</b>
<ul>
<li>More intelligent, emotionally sensitive, and context-aware replies.
Better understanding of complex queries.
Support for in-depth therapy-style conversations (with safety filters).</li>
</ul>



# Final Summary 

> <b>“MindMitra</b> <i>is not just a chatbot</i>—it’s a comprehensive mental health assistant powered by AI. Currently running on DialoGPT and our custom <b>emotion model MindBERT</b>, it provides <b>voice-enabled, multilingual emotional support</b> etc. In the future, we’re integrating SOS crisis detection using fine-tuned BERT, and a safe community space for user interaction. With ChatGPT API in future integration, <b>MindMitra aims to evolve into an emotionally intelligent digital therapist, ensuring no one ever feels alone.”</b>
