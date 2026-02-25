Project Description

This project implements an environmental sound classification system using a Random Forest classifier trained on the UrbanSound8K dataset.

Audio signals are processed using MFCC (Mel-Frequency Cepstral Coefficients) feature extraction through librosa. The extracted features are normalized using StandardScaler before being fed into a RandomForestClassifier with 100 estimators.

The trained model achieves an accuracy of 89.3% on the test set.

The final model and scaler are serialized using joblib for inference on new audio files.

Model Details

Feature Extraction: MFCC

Feature Scaling: StandardScaler

Classifier: Random Forest (100 trees)

Test Accuracy: 89.30%

Evaluation Metrics:

Precision

Recall

F1-score

Confusion Matrix
