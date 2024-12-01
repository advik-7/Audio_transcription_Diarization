# Audio Transcription and Diarization with Whisper and Resemblyzer

This project uses OpenAI's Whisper model for audio transcription and Resemblyzer for speaker diarization to process audio conversations. The system transcribes the conversation into text and assigns speaker labels (e.g., Speaker 1, Speaker 2) based on the detected speakers in the audio.

## Features
- **Audio Transcription**: The audio is transcribed using Whisper, which provides accurate text output from audio.
- **Speaker Diarization**: Speaker diarization is performed using Resemblyzer and Spectral Clustering to detect and label the speakers in the conversation.
- **Timestamp Matching**: The transcription is matched with speaker labels based on timestamps to produce a conversation format.
- **Customizable Parameters**: You can adjust parameters like the segment duration and number of speakers in the audio.

## Requirements
- Python 3.7+
- `whisper` library for transcription
- `resemblyzer` for speaker diarization
- `librosa` for audio processing
- `scikit-learn` for spectral clustering

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/audio-transcription-diarization.git
cd audio-transcription-diarization
