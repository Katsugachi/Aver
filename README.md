# Aver
Open Source powerful transcription tool. <br>
A lightweight, browser-based audio and video transcription tool. Upload files, record directly from your microphone, or paste links to transcribe media into editable text.

## Features

- **File Upload**: Support for MP3, WAV, M4A, MP4, WEBM, MOV, OGG, AAC, and FLAC formats
- **Live Recording**: Record audio directly from your microphone with real-time timer
- **In-Browser Processing**: Uses Moonshine Base for efficient transcription
- **Project Management**: Organize multiple transcriptions in a sidebar with quick access
- **Editable Transcripts**: Full-featured text editor with segment-level editing and formatting
- **Dark/Light Theme**: Toggle between themes for comfortable viewing
- **Export**: Download transcripts as plain text files
- **Persistent Storage**: Saves projects locally using IndexedDB for offline access

## How It Works

1. Upload an audio/video file, record from your microphone, or select a project
2. The transcription model processes your media locally in the browser
3. Edit and refine the generated transcript with the built-in editor
4. Export your final transcript as a text file

## Technology

- Pure JavaScript (no build step required)
- Web Audio API for microphone recording
- IndexedDB for persistent project storage
- Moonshine Base for on-device transcription

## Browser Support

Works in Chrome, Firefox, Safari, and Edge. Requires WebAssembly and Web Audio API support.
