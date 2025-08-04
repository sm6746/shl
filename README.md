# 📚 Grammar Scoring Engine – SHL Hiring Assessment

This repository contains a Kaggle notebook developed for the **SHL Hiring Assessment - Grammar Scoring Challenge**. The goal of the competition is to build a machine learning model that predicts **grammar scores** based on **spoken audio samples** and associated metadata.

---

## 🏁 Competition Overview

- 🎯 **Competition Name:** SHL Hiring Assessment – Grammar Scoring  
- 🧠 **Objective:** Predict grammar scores from .mp3 audio files  
- 📁 **Dataset Includes:**
  - `train.csv`, `test.csv`
  - `.mp3` audio files for each sample

---

## 📂 Repository Contents

| File/Folder                        | Description                                                |
|-----------------------------------|------------------------------------------------------------|
| `notebookd97e4780df (1).ipynb`    | Main Kaggle notebook: EDA, preprocessing, model training   |
| `README.md`                       | This file                                                  |

---

## 🛠️ Features Implemented

- 📥 **Data Loading & Preprocessing**  
  Handling of CSV files and matching audio samples

- 🎵 **Audio Feature Extraction**  
  Techniques like **MFCCs** and spectral embeddings

- 🤖 **Model Building**  
  Implemented **regression models** and/or **deep learning architectures**

- 📊 **Model Evaluation**  
  RMSE (Root Mean Square Error) as the primary evaluation metric

- 📈 **Inference Pipeline**  
  Generates predictions on the test set for final submission

---

## 🧪 Tools & Technologies

- 🐍 Python 3.x
- 📊 Pandas, NumPy
- 🔉 Librosa / torchaudio (for audio processing)
- 🤖 Scikit-learn / PyTorch / TensorFlow (for modeling)
- 📓 Jupyter / Kaggle Notebook Environment

---

## 🚀 How to Use

1. Clone the repository or download the notebook.
2. Upload it to [Kaggle Notebook](https://www.kaggle.com/code) or run locally in Jupyter.
3. Place the `train.csv`, `test.csv`, and audio files in the correct working directory.
4. Run the notebook cells sequentially for:
   - Data exploration
   - Feature engineering
   - Model training & validation
   - Test predictions & submission generation

---

## 📌 Notes

- 🔐 The dataset is only available to registered Kaggle participants.
- 🧠 The project can be further improved with advanced audio embeddings like Wav2Vec or Whisper.

---

## 📄 License

This project is for educational and competition purposes. Refer to the [Kaggle competition rules](https://www.kaggle.com/competitions) for data usage guidelines.

---

## 🙌 Acknowledgments

- Thanks to **SHL & Kaggle** for organizing the challenge.
- Inspired by speech processing and evaluation techniques in NLP & Audio ML.

---
