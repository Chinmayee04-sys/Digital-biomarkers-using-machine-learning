# Digital-biomarkers-using-machine-learning
This project aims to detect potential mental health conditions such as stress, anxiety, and depression risk using facial emotion recognition powered by neural networks.
Facial expressions are considered digital biomarkers that reflect a person's emotional state. By analyzing facial expressions captured through a webcam or image input, machine learning models can identify emotional patterns that may indicate mental health conditions.

In this project, a Convolutional Neural Network (CNN) is used to analyze facial images and classify emotions such as happy, sad, angry, fear, neutral, surprise, and disgust. The detected emotions are then analyzed over time to generate insights about a user's emotional behavior.

The system records detected emotions and calculates their distribution. Based on these emotion patterns, an AI logic module predicts possible mental health conditions such as mild emotional imbalance, anxiety risk, stress level, or possible depression risk.

The project also includes a web dashboard where users can:

View detected emotions

Monitor emotion distribution graphs

See emotion trends over time

Generate a mental health analysis report
Technologies Used

Machine Learning

Python

TensorFlow / Keras

Convolutional Neural Networks (CNN)

Computer Vision

OpenCV

FER (Facial Emotion Recognition)

Backend

Flask API

Frontend

Next.js

React

TailwindCSS

Data Processing

Pandas

NumPy

Matplotlib

Emotion Categories Detected

The model detects the following facial emotions:

Happy

Sad

Angry

Fear

Neutral

Surprise

Disgust

Mental Health Insight Logic

Emotion patterns are analyzed to estimate possible mental health conditions:

Emotion Pattern	Possible Insight
High Sadness	Possible Depression Risk
High Fear	Anxiety Risk
High Anger	Stress Level
High Happiness	Healthy Emotional State
Mostly Neutral	Normal Mental State
Example Output

Emotion Distribution Example:

Happy: 30%
Sad: 20%
Angry: 10%
Fear: 5%
Neutral: 35%

AI Predicted Condition:

Mild Emotional Imbalance
Disclaimer

This project provides AI-based insights for educational and research purposes only.
It does not replace professional medical diagnosis.

Future Improvements

• Integrate smartphone sensor data (activity, GPS, sleep patterns)
• Add voice emotion detection
• Use larger emotion datasets for improved accuracy
• Build a mobile application version
