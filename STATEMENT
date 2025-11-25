Project: Simple Voice Assistant (Alexa-like)
This is a basic voice-controlled personal assistant built in Python using several popular libraries. It listens for voice commands, processes them, and responds with speech and actions.
Key Features:

Voice Input & Recognition
Uses speech_recognition library with Google Speech Recognition API to listen through the microphone and convert speech to text.
Activates only when the user says "Alexa" (acts as a wake word).

Text-to-Speech Output
Uses pyttsx3 to convert responses into spoken audio.
Configured to use a female voice (second voice in the system list).

Available Commands & Actions:
Play [song name] → Plays the requested song on YouTube using pywhatkit.playonyt().
What’s the time? → Tells the current time in 12-hour format (e.g., "03:30 PM").
Who is [person name]? → Searches Wikipedia and reads a one-sentence summary about the person.
Tell me a joke → Tells a random programming or general joke using pyjokes.
受理 Are you single? → Playfully replies: "I am in a relationship with Wi-Fi."
Date? → Humorously responds: "Sorry, I have a headache today."
Any unrecognized command → Politely asks to repeat the command.

Error Handling
Handles cases where speech is unclear (UnknownValueError) or internet is down (RequestError).
Gracefully handles Wikipedia errors (page not found or ambiguous search).

Continuous Listening
Runs in an infinite loop, always listening for the next command.


Libraries Used:

speech_recognition – for listening and understanding voice
pyttsx3 – offline text-to-speech
pywhatkit – to play YouTube videos
wikipedia – to fetch information
pyjokes – for jokes
datetime – to get current time

Summary:
This is a fun, beginner-friendly voice assistant inspired by Amazon Alexa, capable of playing music, telling time, answering "who is" questions, cracking jokes, and giving witty responses — all controlled completely by voice.
Great project for learning voice automation in Python!
