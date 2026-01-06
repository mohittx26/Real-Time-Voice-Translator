# 🎙️ Real-Time Voice Translator

A **Python-based Real-Time Voice Translator** that converts spoken language from one language to another using speech recognition, translation services, and text-to-speech technology.  
This project is developed as a **major academic project** and focuses on simplicity, real-time performance, and usability.

---

## 📌 Project Overview

In today’s global environment, language barriers often create challenges in effective communication.  
The **Real-Time Voice Translator** is designed to reduce this gap by allowing users to speak in one language and instantly hear the translated output in another language.

The system captures voice input through a microphone, converts it into text, translates it into the selected target language, and finally converts the translated text back into speech.  
This enables smooth and natural communication without the need for typing or manual translation.

---

## 🚀 Features

- Real-time speech-to-speech translation  
- Supports multiple languages (English, Hindi, Bengali, Gujarati, and more)  
- Simple and user-friendly graphical interface  
- Voice input through microphone  
- Translated output in audio format  
- Easy to run on local PC  

---

## 🛠️ Tools & Technologies Used

- **Programming Language:** Python  
- **GUI Framework:** Tkinter  
- **Speech Recognition:** SpeechRecognition library  
- **Translation:** Translation API (via deep-translator / Google Translate)  
- **Text-to-Speech:** gTTS (Google Text-to-Speech)  
- **Audio Processing:** PyAudio, playsound  

---

## 💻 System Requirements

- Python 3.8 – 3.12  
- Windows OS (recommended)  
- Working microphone and speakers  
- Internet connection (required for speech recognition and translation)  

---

## ⚙️ How to Run the Project Locally
## 1️⃣ Clone the Repository

```bash
git clone https://github.com/mohittx26/Real-Time-Voice-Translator.git
cd Real-Time-Voice-Translator
2️⃣ Create a Virtual Environment
python -m venv env

3️⃣ Activate the Virtual Environment (Windows)
env\Scripts\activate

4️⃣ Install Required Dependencies
pip install -r requirements.txt


⚠️ If PyAudio installation fails on Windows, download the compatible wheel from:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio

Then install it using:

pip install PyAudio-<version>.whl

5️⃣ Run the Application
python main.py
