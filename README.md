# 🗣️ Voice-based Chatbot using Python  

##  Overview
This project is a **voice-enabled chatbot** built in Python.  
It listens to the user's speech, converts it to text, fetches information from **Wikipedia**, and responds back with **text-to-speech**.  
It is designed to run on **Raspberry Pi** and can be configured to start automatically at boot.  

---

##  Features
-  **Speech Recognition** – Converts voice to text using Google Speech Recognition API  
-  **Wikipedia Integration** – Fetches instant answers from Wikipedia  
-  **Text-to-Speech (TTS)** – Responds with human-like voice using pyttsx3  
-  **Autostart on Raspberry Pi** – Runs at boot using `.bashrc` file  
-  **Exit Command** – Say `exit` to stop the chatbot  

---

##  Tech Stack
- **Programming Language**: Python 3  
- **Libraries Used**:  
  - `speech_recognition` – for speech-to-text  
  - `pyttsx3` – for text-to-speech  
  - `wikipedia` – to fetch answers  
  - `time, os, warnings` – system utilities  

---


