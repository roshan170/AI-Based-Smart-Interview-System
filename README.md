# AI-Based-Smart-Interview-System
AI-powered interview system with resume analysis, job role prediction, real-time facial emotion detection, speech recognition, automated answer evaluation, and Power BI dashboard.

## Project Overview

An AI-powered interview assessment system that integrates resume analysis, job role prediction, facial emotion recognition, speech-to-text conversion, and automated answer evaluation.

## Key Features

* **Resume Analysis:** Extracts text and identifies relevant skills using NLP.
* **Job Role Prediction:** Maps extracted skills to suitable job categories.
* **Question Selection:** Retrieves role-specific questions and reference answers from a dataset.
* **Emotion Detection:** Uses OpenCV and a CNN-based facial expression recognition model.
* **Speech Recognition:** Converts spoken interview responses into text.
* **Answer Evaluation:** Uses TF-IDF and cosine similarity to calculate answer similarity scores.
* **Power BI Dashboard:** Visualizes interview scores, detected emotions, and candidate performance.

## Technology Stack

Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, NLP, OpenCV, TensorFlow/Keras, Speech Recognition, Power BI.

## Project Workflow

Resume Upload → Text Extraction → Skill Detection → Job Role Prediction → Question Selection → Emotion Detection and Speech Capture → Answer Evaluation → Result Storage → Dashboard.

## Installation

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open the notebook in Jupyter Notebook.
4. Configure the dataset and trained model paths.
5. Run the notebook cells in order and allow camera and microphone access when prompted.

## Evaluation Method

Candidate answers are compared with reference answers using TF-IDF and cosine similarity. The resulting percentage represents text similarity, not a guaranteed measure of factual correctness.

## Limitations

Facial emotion predictions are estimates and cannot reliably establish a candidate's true emotional state, confidence, or job suitability. Automated scores should be reviewed by a human and should not be used as the sole basis for hiring decisions.

## Author

Roshan

## Project Status

Academic / Portfolio Project
