# 🧬 BirdCLEF+ 2025 | Sound Analyses – Bird vs Frog  
*by Aralbek Altynay*  
Biologist & Data Science Enthusiast | Focus: Ecoacoustics, Amphibians, AI for Ecology

---

## 🌿 Project Overview

This repository presents an original machine learning pipeline developed for the **BirdCLEF+ 2025** competition on Kaggle.

🔍 **Objective:**  
Classify audio recordings into two categories — `bird` or `frog` — based on sound alone.  
🧠 **Approach:**  
Deep learning (CNN) on spectrograms, trained with limited audio data.  
🌎 **Context:**  
The model supports biodiversity monitoring in the El Silencio Natural Reserve, Colombia — one of the world’s richest ecosystems.

---

## 📁 Project Structure
birdclef2025-soundanalyses/
├── data/
│   ├── train/
│   │   ├── bird/
│   │   └── frog/
│   └── test/
│       ├── example_bird.png
│       └── example_frog.png
├── models/
│   └── bird_vs_frog_model.h5
├── notebooks/
│   ├── 01_model_training.ipynb
│   └── 02_prediction_submission.ipynb
├── submission/
│   └── submission.csv
├── README.md
├── requirements.txt
└── LICENSE
---

## 🧠 Model Details

- **Architecture**: CNN (Convolutional Neural Network)
- **Input**: Mel Spectrograms of `.ogg` audio files
- **Output**: Probability: `bird` or `frog`
- **Tools**: `TensorFlow`, `Keras`, `Librosa`, `Matplotlib`, `NumPy`, `Pandas`
- **Results**:  
  ✅ Training Accuracy: ~100%  
  ✅ Validation Accuracy: ~65%

---

## 📦 Installation

To install all required packages:

```bash
pip install -r requirements.txt
pip install tensorflow librosa matplotlib numpy pandas

📄 License

This project is released under CC BY-NC-SA 4.0.
Use is permitted for non-commercial research and education only.
