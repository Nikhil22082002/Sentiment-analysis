Sentiment Analysis Project

This is a Flask-based web application for sentiment analysis. The application takes input audio files, processes them using Librosa, and predicts sentiment using a pre-trained TensorFlow model.

Features

User-friendly web interface built with Flask.

Sentiment prediction from audio files.

Audio preprocessing using Librosa.

Deep learning-based sentiment classification using TensorFlow/Keras.

Prerequisites

Make sure you have the following installed:

Python (>= 3.8)

Pip (package manager for Python)

Libraries Used

The following libraries are required for this project:

Flask: For building the web application.

Librosa: For audio processing.

NumPy: For numerical computations.

TensorFlow/Keras: For loading the pre-trained model and making predictions.

Installation

Clone this repository:

git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install the dependencies:

pip install -r requirements.txt

Place your pre-trained TensorFlow model in the model/ directory.

Running the Application

Start the Flask server:

python app.py

Open your web browser and go to http://127.0.0.1:5000/ to use the application.

Usage

Upload an audio file in the specified format (e.g., .wav).

The application processes the audio and predicts the sentiment.

The predicted sentiment will be displayed on the screen.

