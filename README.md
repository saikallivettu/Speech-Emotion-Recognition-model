# Speech-Emotion-Recognition-model
---

## Task 2: Speech Emotion Recognition (SER) using Deep Learning

### Project Objective
An AI system developed to detect distinct human emotional states from voice recordings. The model parses unstructured audio signals to accurately classify speech inputs into five core emotional profiles: **Happy**, **Sad**, **Angry**, **Neutral**, and **Fearful**.

### Audio Features Extracted
- **MFCCs (Mel-Frequency Cepstral Coefficients):** Maps spectral and timbre characteristics of vocal tracts.
- **Pitch/Frequency Variations & Energy:** Tracks structural changes in vocal tones and signal intensity delivery.

### Tech Stack & Frameworks
- **Language:** Python
- **Libraries:** Librosa (Audio Analysis), TensorFlow/Keras (Deep Learning Framework), Scikit-Learn, NumPy, Matplotlib
- **Architecture:** 1D Convolutional Neural Network (CNN) engineered to extract temporal auditory patterns.

### Model Evaluation
- Fixed data variance to completely eliminate training overfitting.
- Real-time training and validation metrics mapping acoustic variations cleanly across emotional boundaries with high overall testing accuracy.
