#  Jarvis AI Assistant (Python)

This project is a simple voice-controlled assistant inspired by *Jarvis* from Iron Man.  
It can listen to your voice, understand commands, speak back, and perform real tasks like:

- Searching Wikipedia 
- Opening websites 
- Playing Music 
- Telling Time 
- Launching Folders & Files 
- And more…


##  Features
| Feature | Description |
|--------|-------------|
| Voice Input | Understands speech using `speech_recognition` |
| Voice Output | Speaks responses with `pyttsx3` |
| Info Search | Fetches summaries from Wikipedia |
| Web Automation | Opens YouTube, Google, GitHub, etc. |
| Local Automation | Opens folders / plays music on PC |


##  Requirements

Run the following before executing:

     pip install pyttsx3
     pip install SpeechRecognition
     pip install wikipedia
     pip install pyaudio   # If missing

 Works best on Windows (uses sapi5 voice engine).

  How to Run
   ```bash

python jarvis.py
