# Speech-Recognition-System

COMPANY: CODTECH IT SOLUTIONS

NAME: PAGIDIPALLI PAUL

INTERN ID: CT12PBM

DURATION: 8 WEEKS

MENTOR: NEELA SANTHU

##Description:

This project implements a speech recognition system that transcribes large audio files into text efficiently. It utilizes the SpeechRecognition library for converting speech to text and pydub for audio processing. The script offers two different methods for handling large audio files:

Silence-Based Splitting – The audio is split into chunks based on silent intervals.

Fixed-Interval Splitting – The audio is divided into predefined time intervals.

This approach ensures improved accuracy in transcription by breaking down long recordings into smaller, more manageable segments.

How It Works
The system processes an audio file by performing the following steps:

Load the Audio File – The script reads the input file using pydub.

Chunking – The audio is divided using either silence-based or fixed-interval methods.

Speech Recognition – Each chunk is transcribed using Google’s Speech-to-Text API.

Text Compilation – The transcriptions from all chunks are combined to produce the final output.

This method reduces errors caused by long continuous speech, enhancing transcription accuracy.

Project Features
Handles Large Audio Files – Efficiently processes lengthy recordings without performance issues.

Two Splitting Methods – Users can choose between silence-based and fixed-interval chunking.

Error Handling – Provides error handling for unrecognized speech segments.

Modular Code – Functions are designed for easy customization and reuse.

Automatic Chunk Storage – Saves audio chunks for debugging or future use.

Installation & Dependencies
Before running the script, install the required libraries:

pip install SpeechRecognition pydub
Additional setup:

FFmpeg – Required for handling audio formats in pydub.

How to Use
Provide an Audio File – Place your audio file in the specified directory.

Run the Script – Update the path variable with your file location and execute main.py.

Choose a Transcription Method – The output will be generated using either silence-based or fixed-interval splitting.

Applications
Meeting & Lecture Transcription

Podcast & Interview Processing

Subtitling for Videos

Call Center Analytics
