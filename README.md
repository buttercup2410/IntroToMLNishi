# ECG Classification using CNN-BiLSTM and Lightweight CNN-LSTM

This project implements two deep learning models for ECG signal classification using the ECG5000 dataset:
- **Method A**: A deep learning model combining CNN with BiLSTM
- **Method B**: A lightweight hybrid model using CNN and LSTM
- **Method C**: A K-Nearest Neighbors (KNN) baseline for comparison

---

## 📊 Dataset

- **Name**: ECG5000
- **Source**: UCR Time Series Archive
- **Format**: Provided as `.pickle` files:
  - `ECG5000_train.pickle`
  - `ECG5000_validation.pickle`

Each sample is structured as:  
``[label, feature_1, feature_2, ..., feature_n]``

---

## 🔧 Project Structure

├── main.ipynb # Full implementation

├── ECG5000_train.pickle # Training dataset

├── ECG5000_validation.pickle# Validation dataset

├── README.md # Project documentation

---

## 📦 Dependencies

Install all necessary packages via pip:

```bash
pip install -r requirements.txt

pip install tensorflow scikit-learn pandas numpy
