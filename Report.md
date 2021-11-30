# Speech Emotion Recognition
By: Rawabi Alharbi, Dimah Albunayyih

## Abstract
Speech Emotion Recognition (SER) is the act of recognizing human emotion from speech. This is the advantage of the fact that voice often reflects underlying emotion through tone and pitch. SER can be beneficial for call centers that are giving health care support for elderly people and emergency call centers. The proposed project is based on speech emotion recognition is giving greater priority to calls with emotions such as fear, anger, and sadness, and less priority to calls with neutral speech and happiness.

## Design
The four datasets provided on Kaggle were stored as CSV files. The first process was clean the datasets, made them as one format and concatenate them. Then we did EDA to understand the data. After that we started the CNN to predict the speech emotion.

## Data
In this project, we used the data from Github (https://github.com/inparallel/SaudiNewsNet). It contains a set of 31,030 Arabic newspaper articles along with metadata, extracted from various online Saudi newspapers.

## Algorithms
We applied different Augmentation techniques (Noise injection, stretching and pitch), and applied feature extraction techniques (zero crossing rate, chroma_stft, MFCC, RMS and melSpectogram) to extract the most important features from the audio files and then we applied neural network algorithms using convolution and dense layers with (relu and softmax) activation functions.

## Tools
* Technologies: Python, Jupyter notebook.
* Libraries: NumPy, Pandas, Sklearn, librosa, Matplotlib, Seaborn

## Communication
In addition to the slides and visuals presented, we will share our work on our Github accounts
* https://github.com/RawabiKhalaf/speech-emotion-recognition/new/main/Source_code.ipynb
* https://github.com/DimahAlbunayyih/T5_bootcamp_projects.git
