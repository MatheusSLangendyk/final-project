# Emotion Detection Application

## Author
Matheus Langendyk

## Purpose
This is the final project for the IBM Python Developer with Flask course. It is a Flask-based web application that uses IBM Watson NLP's Emotion Predict function to analyze a piece of text and detect the emotions expressed in it (anger, disgust, fear, joy, and sadness), along with the dominant emotion.

## Features
- `EmotionDetection` package with an `emotion_detector` function that calls the Watson NLP Emotion Predict API and returns emotion scores plus the dominant emotion.
- Error handling for blank/invalid input (status code 400), returning `None` values and a user-friendly message.
- Flask web server (`server.py`) with a simple UI (`/`) and an `/emotionDetector` endpoint that returns the analysis as formatted text.
- Unit tests (`test_emotion_detection.py`) validating the dominant emotion for sample statements covering joy, anger, disgust, sadness, and fear.
- Code verified with Pylint static code analysis (10.00/10).
