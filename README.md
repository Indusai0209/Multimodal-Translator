# Multimodal-Translator

## Overview

The   Multimodal Translator   is a Flask-based web application designed to perform language translation on text, audio, and video inputs. It supports numerous languages using Google Translate and integrates speech recognition and synthesis for handling both audio and video content.

## Features

-   Text Translation  : Translate text from any source language to a target language.
-   Audio Translation  : Upload audio files, transcribe them, and translate the transcription to the desired language.
-   Video Translation  : Extract audio from a video, translate it, and re-integrate the translated audio back into the video.

## Technologies Used

-   Flask  : Web framework for Python.
-   Googletrans  : For text translation.
-   SpeechRecognition  : To recognize speech from audio files.
-   gTTS (Google Text-to-Speech)  : For converting text into speech.
-   MoviePy  : For video editing and extracting audio from video files.
-   HTML, CSS, JS  : Frontend technologies to serve the web interface.

## Supported Languages

The application supports a wide range of languages including but not limited to:
- English
- Spanish
- French
- Hindi
- Chinese (Simplified & Traditional)
- Arabic
- German
- Many more (refer to the `languages` dictionary in the code for full support).

## Setup Instructions

1.   Clone the Repository  :
    ```bash
    git clone https://github.com/Indusai0209/Multimodal-Translator.git
    ```

2.   Install Dependencies  :
    Navigate to the project directory and run:
    ```bash
    pip install -r requirements.txt
    ```

3.   Run the Application  :
    Start the Flask application by running:
    ```bash
    python app.py
    ```
   The app will be hosted locally at `127.0.0.1:8000`.

## Usage

### Text Translation:
1. Navigate to the home page.
2. Enter the text to be translated.
3. Select the target language.
4. The translated text will be displayed on the screen.

### Audio Translation:
1. Upload an audio file (in supported formats like `.wav` or `.mp3`).
2. Select the target language.
3. The application will transcribe and translate the audio.
4. The translated text and audio file will be made available for download.

### Video Translation:
1. Upload a video file.
2. The app will extract the audio, transcribe it, and translate it into the target language.
3. The translated audio will be embedded back into the video, and the new video file will be made available for download.
