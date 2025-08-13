# EEG-Based Eye State Monitoring Using Artifact Features

This project focuses on **eye state monitoring (open vs. closed)** using EEG signals. Unlike conventional EEG preprocessing approaches that remove EMG artifacts as noise, this project leverages EMG-related artifacts as **useful features** for differentiating eye states.

## Key Features

* **Data Acquisition**: EEG signals recorded during eye-open and eye-closed conditions.
* **Artifact Utilization**: EMG artifacts in EEG channels are exploited as discriminative features instead of being removed.
* **Feature Extraction**:

  * Power Spectral Density (PSD) of EEG channels
  * EMG artifact strength as additional features
  * Outlier removal and preprocessing performed before feature extraction
* **Machine Learning Models Tested**:

  * **LSTM**: 71.1% accuracy
  * **SVM**: 71.1% accuracy
  * **XGBoost**: 84.44% accuracy
* **Applications**:

  * Driver drowsiness detection
  * Fatigue monitoring
  * Brain–computer interfaces
  * Other eye-state dependent systems



 
