# Indoor Localization Using Deep Learning on UJIIndoorLoc Dataset

This project focuses on building an indoor positioning system using WiFi RSSI signal data from the UJIIndoorLoc dataset. Deep Learning techniques are employed to estimate the localization error for predicting accurate indoor positions.


## Dataset

- **Name**: UJIIndoorLoc  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ujiindoorloc)  
- **Description**: The dataset contains WiFi signal strengths (RSSI) from 520 WAPs measured at various locations within three buildings of Universitat Jaume I.


## Models Used

The following Deep Learning models were implemented and evaluated:

-  LSTM (Long Short-Term Memory)
-  Bidirectional LSTM
-  Dense Neural Networks

These models aim to minimize localization error (in meters) using RSSI fingerprints.


## ⚙️ Workflow

1.  Data Preprocessing & Cleaning  
2.  Train-Test Splitting  
3.  Model Building (LSTM, BiLSTM, Dense)  
4.  Model Training  
5.  Evaluation via Localization Error


##  Results

- **Primary Metric**: Localization error (in meters)
- **Goal**: Reduce mean error using deep learning models
- Model comparison and error plots are included in the notebook.


##  Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Google Colab


