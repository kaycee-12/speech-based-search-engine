
# 🔊 Voice Search Assistant

This is a simple Python program that uses voice recognition to take a search query from the user and opens Google search results in the default web browser. It also provides spoken feedback using text-to-speech.

## 📋 Features

- Listens to your voice command via microphone.
- Recognizes spoken words using Google's Speech Recognition API.
- Speaks prompts and responses using a text-to-speech engine.
- Opens a web browser with the Google search results for your query.

## 🚀 Requirements

Before running this script, you need to install the following Python packages:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> **Note**: `pyaudio` can be tricky to install on some systems. If you encounter issues, look for system-specific instructions or use a pre-built wheel.

## 🛠️ How It Works

1. The script starts and prompts the user to speak a query.
2. It listens through the microphone.
3. It converts the audio into text using the Google Speech Recognition API.
4. It opens the default web browser with the Google search results for the recognized query.
5. It uses a speech engine to read back the query or provide error messages.

## 🧠 Usage

To run the script:

```bash
python voice_search.py
```

After running, speak clearly into your microphone when prompted.

## 📌 Example

```
Listening...
What do you want to search for?
Recognizing...
You said: weather today
[Opens Google with search: "weather today"]
```

## ❗ Troubleshooting

- **Microphone not working**: Make sure your microphone is properly connected and accessible.
- **Recognition errors**: Ensure you have an internet connection; the Google API requires it.
- **PyAudio install issues**: You may need to install system-specific dependencies (like `portaudio`).

## 📄 License

This project is licensed under the MIT License.
