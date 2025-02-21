# 📜 Media Transcription using OpenAI Whisper

## 🎯 Overview
This Python program scans a directory for audio and video files, transcribes them using OpenAI's Whisper model, and saves the transcriptions in JSON format.

## 🚀 Features
- **Folder Parsing**: Recursively scans for media files.
- **Transcription**: Uses the Whisper model for accurate speech-to-text conversion.
- **Structured Output**: Saves transcriptions in JSON format.

## 📦 Requirements
Before running the script, install the required dependencies:
```bash
pip install -r requirements.txt
```


## 🛠 Usage
Run the script using:
```bash
python whisper_transcript.py
```

### Expected Output
- The script scans `media/`.
- Transcribes each media file.
- Saves results in `transcript/` as JSON.

## 📝 Example JSON Output
```json
{
  "file": "media_files/sample.mp3",
  "transcription": "Hello, this is a sample transcription."
}
```

## 📌 Notes
- The script uses the `tiny` Whisper model for faster processing.
- Modify the `extensions` list in the script to support additional file formats.

## 🏆 Contributing
Feel free to fork this repository and submit pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.
