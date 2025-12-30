# 🧠 EEG Classification Model 

This project focuses on building a machine learning–based classification model to analyze and classify EEG (Electroencephalogram) signals, with a primary emphasis on detecting epileptic seizure activity. The work is carried out as part of the **IE6400 – Foundations of Data Analytics Engineering** course.

---

## 📌 Project Overview

Electroencephalography (EEG) signals play a critical role in neurological research and clinical diagnosis, particularly for epilepsy. This project leverages publicly available EEG datasets to preprocess signals, extract meaningful features, train classification models, and evaluate their performance in identifying seizure patterns.

---

## 📂 Datasets Used

### 1️⃣ CHB-MIT EEG Dataset
- EEG recordings collected from pediatric epilepsy patients
- Includes seizure and non-seizure signals
- Widely used benchmark dataset in epilepsy research

### 2️⃣ Bonn EEG Dataset
- Pre-segmented EEG recordings
- Specifically focused on epileptic seizure activity

---

## 🧪 Methodology

1. Data preprocessing and signal cleaning  
2. Feature extraction from EEG signals  
3. Train, validation, and test data splitting  
4. Model training and tuning  
5. Performance evaluation using standard metrics  
6. Visualization of signals and results  

---

## 📈 Data Visualization & Signal Analysis

To better understand the characteristics of EEG signals across different categories, multiple visual analyses were performed.

### 🔹 Amplitude Distribution Across EEG Categories
The histogram below illustrates the amplitude distribution for different EEG sets, highlighting variations between normal, interictal, and seizure signals.

<img width="1790" height="1025" alt="aptitude_distribution" src="https://github.com/user-attachments/assets/ea4441c6-7f37-4099-91d5-44d148a26ad0" />


---

### 🔹 Sample EEG Signals
Representative EEG signal samples from each category are visualized to observe temporal patterns and signal variability.

<img width="1789" height="1229" alt="sample" src="https://github.com/user-attachments/assets/6d787d15-ba3f-4e82-af50-ceacfc5c67dc" />


---

### 🔹 Original vs Processed EEG Signals
This comparison shows the effect of preprocessing techniques applied to raw EEG signals, demonstrating noise reduction and signal smoothing.

<img width="1489" height="1190" alt="eeg_signal_processing" src="https://github.com/user-attachments/assets/9fe70ff7-a4a1-44b4-b4f9-819077997399" />


---

## 📊 Results

The model demonstrates effective classification of epileptic and non-epileptic EEG signals. Detailed results and performance analysis are provided in the project report.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib
- Scikit-learn

---

## 🚀 Future Enhancements

- Deep learning models (CNNs, RNNs)
- Advanced signal processing techniques
- Real-time EEG classification
