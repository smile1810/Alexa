# Alexa
This Python program is a simple voice assistant that listens for the wake word “Alexa,” recognizes spoken commands, and responds using text-to-speech. It can play YouTube videos, tell the time, answer “who is” questions using Wikipedia, tell jokes, and interact with the user in real time.
# Voice Assistant Project (Python)

This project implements a simple voice-controlled assistant similar to
Amazon Alexa using Python libraries such as: - `speech_recognition` for
converting speech to text\
- `pyttsx3` for text-to-speech\
- `pywhatkit` for playing YouTube videos\
- `wikipedia` for fetching summaries\
- `pyjokes` for jokes\
- `datetime` for time-based responses

## Features

-   Play songs on YouTube\
-   Tell the current time\
-   Provide information about people using Wikipedia\
-   Tell jokes\
-   Respond to simple conversation prompts

## How to Run

1.  Install dependencies:

        pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes

2.  Run the script:

        python alexa.py

3.  Speak commands starting with the wake word **"Alexa"**.

## Notes

-   Make sure your microphone works properly.
-   Requires an active internet connection for web-based features.
