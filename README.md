# Audio-Based Emotion Prediction 🎵🔊

## Overview  
This project utilizes deep learning and audio signal processing techniques to **predict human emotions** from speech. By analyzing features like tone, pitch, and intensity, the model classifies emotions such as **Anger, Happiness, Sadness, Neutral, Fear, and Disgust**.

## Dataset  
We used two datasets:  
- **CREMA-D** (7,442 audio clips from 91 actors)  
- **TESS** (2,800 audio clips from 2 actresses)  

These datasets provide high-quality WAV files with labeled emotions.

## Methodology  
- **Feature Extraction:** MFCC, ZCR, RMSE  
- **Models Used:**  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
  - Convolutional Neural Network (CNN-LSTM)  

The **CNN-LSTM model** achieved the best performance.

## Installation  
To run this project, install the required dependencies:  
```bash
pip install -r requirements.txt

## Results 🏆  
- **CNN-LSTM achieved high accuracy** in predicting emotions.  
- **Feature extraction** significantly improved classification performance.  

## Future Work 🚀  
- Enhance model interpretability using **Explainable AI (XAI)**.  
- Extend the system to **real-time emotion detection** in applications.  

## References 📚  
- [CREMA-D Dataset](https://github.com/CheyneyComputerScience/CREMA-D)  
- [TESS Dataset](https://tspace.library.utoronto.ca/handle/1807/24487)  

## License 📜  
This project is for educational purposes. Feel free to use it with credit.  
