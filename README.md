# 🎵 Music Genre Classification using Machine Learning

This project classifies music genres using Machine Learning techniques and audio feature analysis. The system analyzes extracted audio features such as MFCCs, spectral centroid, chroma features, tempo, and spectral bandwidth to predict the genre of a music file.

---

# 📌 Project Overview

The main goal of this project is to automatically identify the genre of music files using supervised machine learning algorithms.

The model is trained using the GTZAN Music Genre Dataset and predicts genres such as:

- Blues
- Classical
- Country
- Disco
- HipHop
- Jazz
- Metal
- Pop
- Reggae
- Rock

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Librosa
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Dataset

Dataset Used:
GTZAN Music Genre Dataset

The dataset contains:
- 1000 audio files
- 10 music genres
- Extracted audio features

---

# ⚙️ Features Used

The project uses audio features such as:

- MFCC (Mel Frequency Cepstral Coefficients)
- Chroma Features
- Spectral Centroid
- Spectral Bandwidth
- Tempo
- RMS Energy
- Zero Crossing Rate

---

# 🧠 Machine Learning Model

Algorithm Used:
- Random Forest Classifier

The model is trained using supervised learning techniques for multi-class genre classification.

---

# 📊 Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Confusion Matrix
- Classification Report

Achieved Accuracy:
- ~85% to 90%

---

# 📁 Project Structure

```bash
MusicGenreClassification/
│
├── dataset/
│   ├── genres_original/
│   ├── features_30_sec.csv
│   └── features_3_sec.csv
│
├── notebook/
│   └── Music_Genre_Classifier.ipynb
│
├── models/
│   └── music_model.pkl
│
├── app/
│
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run the Project

## 1. Clone Repository

```bash
git clone <your-repository-link>
```

## 2. Create Virtual Environment

```bash
python -m venv venv
```

## 3. Activate Virtual Environment

### Windows
```bash
venv\Scripts\activate
```

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## 5. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:
```bash
Music_Genre_Classifier.ipynb
```

---

# 📌 Future Improvements

- Deep Learning implementation using CNN
- Real-time music prediction
- Streamlit web application
- Deployment on cloud platforms
- Multi-label genre classification

---

# 👨‍💻 Author

Shiva Kumar
