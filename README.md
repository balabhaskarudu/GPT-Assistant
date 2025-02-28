GPT Smart Assistant

🚀 Overview

GPT Smart Assistant is a Python-based AI voice assistant that listens to voice commands, processes them using GPT-4o, and responds via text-to-speech. It can also open websites and perform basic automation tasks.

📦 Features

🎙️ Speech-to-Text: Uses speechrecognition to convert voice commands into text.

🧠 AI-powered Responses: Uses OpenAI’s GPT-4o for intelligent replies.

🗣️ Text-to-Speech: Reads responses aloud using pyttsx3.

🌐 Web Automation: Opens Google, YouTube, and other sites on command.

🔧 Easy Setup: Just install dependencies and run the script.

🛠️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/yourusername/GPT-Smart-Assistant.git

cd GPT-Smart-Assistant
python -m pip install --upgrade pip
pip install openai speechrecognition pyttsx3 pyaudio
python app.py
Get the API Key in this https://platform.openai.com/settings/organization/api-keys
2️⃣ Usage

Run the script and speak into the microphone.

The assistant will process your request and respond.

Say "Open Google" or "Open YouTube" to launch a website.

Say "bye" to exit.

🔒 Security Notice

Ensure that your apikey.py or any API key files are not committed to GitHub. Add them to .gitignore.

📝 To-Do (Future Improvements)

Add custom wake word support.

Implement GUI interface.

Support multiple languages.

📜 License

MIT License

🤝 Contribution

Feel free to fork, contribute, and submit pull requests! 🚀
