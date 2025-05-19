🐦 Bird Species Recognition Using Machine Learning

This project focuses on the automated identification of bird species using audio recordings. It utilizes audio signal processing to convert .wav files into spectrograms and then applies a Convolutional Neural Network (CNN) model to classify bird calls into species.

✅ Built for Recognizing three birds:

Common Tern

American Redstart

Red-winged Blackbird

📚 Project Overview

Bird songs are unique to species, making them a reliable input for classification. This project:

Processes bird call .wav audio files

Extracts meaningful acoustic features (MFCCs, spectrograms)

Converts audio into 2D image-like data using spectrograms

Trains a Convolutional Neural Network (CNN) on the spectrograms

Predicts the species of birds from unseen audio samples

🎯 Use Cases:

This system is ideal for birdwatchers, researchers, or conservationists looking to automate bird species detection using sounds.

🧠 Technologies Used

Python	- Programming language

Librosa	- Audio analysis and feature extraction

NumPy, Pandas	- Data handling and processing

Matplotlib	- Visualization of spectrograms

TensorFlow/Keras	- CNN model building and training

Scikit-learn	- Evaluation and comparison


