# TopicTracker

---
A ipywidgets-based dashboard for searching videos based on topic and key phrase.Used MoviePy and OpenAI's whisper/large-v3 transformer to transcribe over 40 Machine Learning videos. Integrated Amazon S3 to store and retrieve video files. Applied NLP techniques with spaCy for key phrase extraction and topic to analyze video transcripts.

## Business Scenario

You work for a training organization that recently developed an introductory course about machine learning (ML). The course includes more than 40 videos that cover a broad range of ML topics. You have been asked to create an application that will students can use to quickly locate and view video content by searching for topics and key phrases.

## Features

- **Video Processing**: Automatically converts video files to audio files (WAV format) for transcription.
- **Speech-to-Text Transcription**: Utilizes pre-trained deep learning models for accurate transcription of audio content into text.
- **Text Analysis**: Extracts key phrases and topics from the transcribed text.
- **Interactive Search**: Provides an interactive search feature for finding videos based on user-defined keywords or topics.

## Usage
1. Log into AWS.
2. Run the main Python script "topictracker.ipynb".

## Dependencies
* Python 3
* Libraries
    * nltk (Natural Language Toolkit)
    * re (Regular Expressions)
    * pandas
    * boto3
    * moviePy
    * torch
    * transformers
    * spaCy
    * ipywidgets
    * IPython.display

