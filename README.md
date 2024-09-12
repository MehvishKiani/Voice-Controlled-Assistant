# Voice-Controlled-Assistant
A Python-based voice-controlled assistant using speech recognition, text-to-speech, and natural language processing. This assistant can recognize voice commands, respond intelligently, and execute various tasks, including creating files and interacting with the user through a GUI.

How to Run
Ensure you have a working microphone connected to your system.
Run the assistant using the following command:

python assistant.py

How It Works
The assistant listens for the trigger phrase "hey Ashal."
Upon activation, it listens for commands, processes them using pre-defined intents, and responds accordingly.
The assistant can perform various tasks, such as creating files, stopping on command, and more.
Requirements
Python 3.x
Tkinter (included with Python)
speech_recognition
pyttsx3
neuralintents
Intent File (intents.json)
To define your custom commands and responses, create an intents.json file structured to suit your requirements.

Troubleshooting
Ensure your microphone is properly configured and accessible by the application.
Check that all dependencies are correctly installed.
Review the intents.json file format for any errors.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.
