# 🎤 Fake Audio Detection with NLP 🔍✨

This project is dedicated to detecting fake audio using cutting-edge **Natural Language Processing (NLP)** techniques. By leveraging **Support Vector Machines (SVM)** and **Convolutional Neural Networks (CNN)**, this project classifies audio as real or fake. It aims to enhance the detection of synthetic or manipulated audio in various contexts, including media authenticity and cybersecurity.

---

## 📋 Features

- 📊 **Dataset Exploration**:
  - Loads and explores audio datasets, ensuring balanced data for classification tasks.
  - Visualizes audio waveforms, spectrograms, and other key features.

- 🧹 **Data Preprocessing**:
  - Extracts audio features like **MFCCs (Mel Frequency Cepstral Coefficients)**.
  - Standardizes and normalizes data for optimal model performance.
  - Splits data into training, validation, and test sets.

- 🤖 **Machine Learning Models**:
  - **Support Vector Machines (SVM)**:
    - Uses linear or RBF kernel for classification tasks.
    - Performs well on smaller datasets with feature engineering.
  - **Convolutional Neural Networks (CNN)**:
    - A deep learning model that processes spectrograms and raw audio data.
    - Captures spatial and temporal patterns in audio data.

- 📈 **Model Evaluation**:
  - Evaluates model performance using metrics like **accuracy**, **precision**, **recall**, and **F1-score**.
  - Visualizes performance with confusion matrices and classification reports.

---

## 🛠️ Technologies Used

- **TensorFlow/Keras**: For building and training CNN models.
- **Scikit-Learn**: For implementing SVM and data preprocessing.
- **Librosa**: For audio feature extraction and visualization.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Pandas** and **NumPy**: For data manipulation.

---

## 📂 Project Structure

- **`NLP_Project.ipynb`**: Jupyter Notebook containing the complete implementation.
- **`data/`**: Directory containing the audio dataset.

---

## 🌟 Contributors

- **Shahad Adel**
- **Sana Araj**
- **Sara Thaer**
- **Deem Alrashidi**
- **Shahad Khalid**
- **Reem Fouad**

---

## 📝 Example Results

### SVM Results:
- **Accuracy**: 85%
- **Precision**: 82%
- **Recall**: 80%
- **F1-Score**: 81%

### CNN Results:
- **Accuracy**: 92%
- **Precision**: 90%
- **Recall**: 91%
- **F1-Score**: 90%

