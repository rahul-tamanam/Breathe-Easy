# Pulmonary Disease Detection

### Following is the implementation of a detection system leveraging CNN-LSTM model for lung related illnesses.
The objective of this initiative is to leverage modern technologies and build a reliable diagnostic tool for the prediction of pulmonary diseases.
Utilizing the ICBHI 2017 challenge database, a benchmark data repository of lung auscultation sounds used in this study for accurate respiratory disease detection I was able to develop a deep learning model that is trained in a sophisticated manner.
By harnessing the power of advanced machine learning techniques, particularly Convolutional Neural Networks (CNNs), and integrating them with Flask, a lightweight web framework, we have created a user- friendly platform capable of automated disease prediction from lung sound recordings.
CNN-LSTM (Convolutional Neural Network - Long Short-Term Memory) is a hybrid deep learning model that combines CNNs for feature extraction and LSTMs for sequential pattern learning. This architecture is particularly useful for analyzing time-series data like lung sounds in lung disease detection.

## How CNN-LSTM Works for Lung Sound Analysis:
-> Feature Extraction with CNN:

+ CNNs are excellent at capturing spatial patterns in spectrograms (visual representations of sound) derived from lung sounds.
+ Convolutional layers detect frequency-based patterns associated with normal and abnormal breathing sounds (e.g., wheezes, crackles).

-> Temporal Pattern Learning with LSTM:

+ LSTMs process sequential data, making them ideal for capturing temporal dependencies in lung sounds.
+ Since lung sounds vary over time, LSTM layers help understand the progression of respiratory anomalies over a sequence.

-> Combining CNN & LSTM for Lung Disease Detection:

+ CNN first extracts meaningful features from spectrograms or Mel-frequency cepstral coefficients (MFCCs).
+ The extracted features are then passed into LSTM layers to learn patterns over time.
+ A fully connected layer and softmax/sigmoid activation help classify different lung conditions (e.g., normal, wheeze, crackle, or disease categories like asthma, COPD, pneumonia).

## Why CNN-LSTM is Effective for Lung Disease Detection:
+ Captures Spatial & Temporal Features: Lung sounds have unique frequency and time-dependent variations. CNN-LSTM efficiently models both.
+ Better Generalization: Unlike traditional methods (e.g., handcrafted feature extraction), deep learning automatically learns complex patterns in the data.
+ Handles Noise & Variability: Lung sounds can vary due to different recording conditions. CNN-LSTM helps extract robust features while preserving essential information.


### Sample Output:
![image](https://github.com/user-attachments/assets/cbc5c9bc-e780-49e9-96ce-f43ab86ffcbe)
![image](https://github.com/user-attachments/assets/6caa64b3-83ad-46fe-9943-73a752296929)

