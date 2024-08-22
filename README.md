# Speech-Emotion-Recognition
This repository contains the code and resources for the Speech Emotion Recognition project, where we classify emotions from speech using machine learning models. We use two datasets: TESS and RAVDESS. The project includes feature extraction using MFCCs and emotion classification using both SVM and LSTM models for comparison.

**Project Overview**
        The goal of this project is to recognize human emotions from speech. We approach this task by using two different datasets and applying feature extraction techniques to prepare the data for classification. We then compare the performance of two different classifiers: Support Vector Machines (SVM) and Long Short-Term Memory (LSTM) networks.

**Datasets**
        TESS (Toronto Emotional Speech Set): Contains audio recordings from two actresses, aged 26 and 64, who speak 200 target words in the neutral, angry, happy, sad, fearful, and disgusted emotions.
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song): Consists of emotional speech and song recordings by 24 actors (12 male, 12 female), covering eight emotional states: calm, happy, sad, angry, fearful, disgust, surprised, and neutral.

**Feature Extraction** 
        We extract Mel-Frequency Cepstral Coefficients (MFCCs) from the audio recordings. MFCCs are a representation of the short-term power spectrum of sound and are commonly used in speech and audio processing.

**Models Used**
Support Vector Machine (SVM)
        SVM is a supervised learning model that analyzes data for classification. It finds the hyperplane that best separates the data into different classes.
Long Short-Term Memory (LSTM)
        LSTM is a type of recurrent neural network (RNN) capable of learning long-term dependencies. It is well-suited for sequential data like speech.
