# Titans-Tech
<b>MindMitra – Tech Stack & Architecture</b>

Current Tech Stack:

<b>1. Frontend (Web App)</b>

React.js – For creating fast, interactive UI.

HTML, CSS, JavaScript – Structure and styling.

Framer Motion / GSAP – For smooth animations.

React Router – For routing between home and chatbot pages.


2. Backend

Flask (Python) – Lightweight backend framework to manage API requests and serve ML model predictions.

Model Integration:

DialoGPT – A fine-tuned transformer-based model from Microsoft, used for conversational dialogue.

MindBERT – A BERT-based custom model trained for emotion classification and intent detection.



3. Database

MongoDB (NoSQL) – To store user data, conversation logs, emotion records, etc.


4. Voice & Language Tools

SpeechRecognition (Python Library) – For converting voice input to text.

gTTS / ResponsiveVoice / Web Speech API – For converting bot’s response back to voice.

Google Translate API – For multilingual support (Hindi, English, French, etc.)



---

What Makes MindMitra Unique (Compared to Others):

<b>Emotion Detection</b> using MindBERT to personalize replies.

Multilingual and Voice Enabled Chatbot.

Completely Offline ML Model (DialoGPT + MindBERT), no dependence on OpenAI’s paid API.

Future Vision for Community & SOS, making it more than just a chatbot—a mental health ecosystem.



---

Future Features & Tech Stack

1. SOS System (Crisis Detection & Emergency Support)

Goal:

To automatically detect if a user is showing suicidal, harmful, or highly distressed behavior based on:

Conversation patterns

Emotion scores

Time spent and frequency


Tech Stack:

2. Community Feature (User-to-User Interaction & Forums)

Goal:

Allow users to join mental health communities, share experiences, and support one another anonymously.

Tech Stack:


---

Planned Integration of ChatGPT API (OpenAI)

Currently:

MindMitra is using DialoGPT locally, which is cost-effective and controllable.


Future Plan:

Integrate OpenAI’s ChatGPT API for:

More intelligent, emotionally sensitive, and context-aware replies.

Better understanding of complex queries.

Support for in-depth therapy-style conversations (with safety filters).



Stack Required:


---

Final Summary for Pitch (Use This for Hackathon Tomorrow):

> “MindMitra is not just a chatbot—it’s a comprehensive mental health assistant powered by AI. Currently running on DialoGPT and our custom emotion model MindBERT, it provides voice-enabled, multilingual emotional support. In the future, we’re integrating SOS crisis detection using fine-tuned BERT, and a safe community space for user interaction. With ChatGPT API in future integration, MindMitra aims to evolve into an emotionally intelligent digital therapist, ensuring no one ever feels alone.”
