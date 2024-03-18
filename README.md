# OpenAI Whisper-Based Speech Recognition
Overview
This Jupyter notebook showcases the implementation and evaluation of an Automatic Speech Recognition (ASR) system using OpenAI's Whisper models, specifically whisper-tiny and whisper-small. Leveraging the power of these models, the project aims to accurately transcribe spoken language into text.

## Features
- Advanced ASR Models: Utilizes OpenAI's Whisper models for high-accuracy speech recognition.
- LibriSpeech Dataset: Trains and evaluates the model on the train.clean.100 split of the LibriSpeech ASR dataset, a standard benchmark in the field.
- Interactive Demo: Includes an interactive section allowing users to test the model with their audio files, powered by Gradio.
- Installation
- To run the notebook, ensure you have the following packages installed:

pip install transformers datasets soundfile librosa gradio

## Using the Whisper Models
This project makes use of the openai/whisper-tiny and openai/whisper-small models for speech recognition tasks. These models have been fine-tuned on a variety of audio data and are capable of delivering high accuracy in transcribing spoken words to text.

## Dataset
The LibriSpeech dataset, specifically the train.clean.100 split, is utilized for training and evaluation. This dataset features 100 hours of clean speech which is ideal for developing and testing ASR systems.

# How to Use
Run the notebook from start to finish. It includes the following sections:

# Dependency installation.
Data preparation using the LibriSpeech dataset.
Model initialization and transcription demonstration.
Interactive testing with your audio files using Gradio.

# Contributing
Contributions are welcome! Feel free to fork the project, make changes, and submit pull requests. If you find any issues or have suggestions, please open an issue in the repository.

