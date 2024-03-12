# voice-assistant-using-python
Here me and my friend has made a project- voice assistant for course scripting language using python. I will explain in details which libraries i have used and why and their importance and i will also provide you the code and my report. 
  libraries:-
    Speech Recognition Library:
        Purpose: Designed for speech recognition, this library supports various engines and APIs, both online and offline.
        Engine/API Support:
            CMU Sphinx (offline)
            Google Speech Recognition
            Google Cloud Speech API
            Wit.ai
            Microsoft Bing Voice Recognition
            Houndify API
            IBM Speech to Text
            Snowboy Hotword Detection (offline)

    PyAudio:
        Purpose: Provides Python bindings for PortAudio v19, enabling audio I/O on multiple platforms. Used for playing and recording audio in Python applications.
        Platforms: Compatible with GNU/Linux, Microsoft Windows, and Apple macOS.
        Requirement: Essential for microphone input. Version 0.2.11 or later is recommended to avoid known memory management bugs during microphone recording.

    PyWhatKit:
        Purpose: A versatile Python library with user-friendly features, especially popular for WhatsApp and YouTube automation.
        Features:
            WhatsApp Automation: Sending messages and images to groups or contacts.
            Image and Text Manipulation: Converting images to ASCII art, converting text to handwriting.
            YouTube Automation: Playing YouTube videos.
            Email Automation: Sending emails with HTML code.
            Easy-to-use: Requires no additional setup, and frequent updates include new features and bug fixes.

    Pyttsx3:
        Purpose: A text-to-speech conversion library in Python that works offline and is compatible with both Python 2 and 3.
        Usage: Invoke the pyttsx3.init() factory function to get a reference to a pyttsx3.Engine instance.
        Voices: Supports two voices - female and male.
        Easy-to-use: Converts entered text into speech, providing a simple and accessible tool for text-to-speech conversion.

summary:
        The given Python code uses PyWhatKit, Pyttsx3, and the Speech Recognition package (speech_recognition) to create a basic voice-activated assistant. In addition to recognising spoken phrases and interacting with the user via voice commands, the assistant may also be used to open websites, play YouTube videos, display the current time, and carry out other operations. Through menu selection, the user can start and manage the assistance.
