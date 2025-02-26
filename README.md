## 🎵**Music Emotion Classification with Machine Learning**
### **Affective Computing on Audio Features using ML Models**
🚀 A machine learning project to classify emotions in music based on Spotify audio features.

----

## 📌 Project Overview
This project aims to predict the emotion of a song based on its audio features extracted from Spotify and other datasets.
Using machine learning models, we classify each song into emotions such as happy, sad, fear, angry, surprise, etc.

Key steps in this project:
1. Data Collection & Cleaning → Extracting and merging music features & emotion labels.
2. Exploratory Data Analysis (EDA) → Understanding feature distributions & correlations.
3. Machine Learning Models → Training & evaluating models like KNN, Logistic Regression, and Random Forest.
4. Feature Importance Analysis → Identifying the most impactful audio features for emotion prediction.
5. Binary Classification for Feature Evaluation → Testing individual feature impact in classification.

## 📂 Project Structure
📁 emotion-music-ml/
│── 📄 README.md                 # Project documentation
│── 📄 requirements.txt          # List of required Python libraries
│── 📄 .gitignore                # Files to ignore in Git
│── 📁 datasets/                 # All datasets used
│   ├── merged_emotion_audio_features.csv  # Final cleaned dataset
│── 📁 notebooks/                # Jupyter notebooks for different stages
│   ├── datacollection&prep.ipynb      # Data collection & preprocessing
│   ├── musicfeature_emtions.ipynb     # Feature extraction & emotion mapping
│   ├── ML.ipynb                       # Machine learning model training
│── 📁 src/                      # Source code
│   ├── data_processing.py       # Functions for cleaning & merging datasets
│   ├── feature_analysis.py      # Feature importance & correlation analysis
│   ├── train_models.py          # ML training & evaluation scripts
│── 📁 results/                   # Model performance reports & graphs
│   ├── feature_importance.png
│   ├── confusion_matrix.png

----

## 📊 Datasets Used
1️⃣ *Music Features Dataset*
- Source: Spotify Audio Features dataset
- Content: Danceability, energy, loudness, valence, tempo, and other musical properties.
2️⃣ *Emotion Labels*
- Source: Last.fm & curated datasets
- Content: Songs labeled with emotions such as happy, sad, angry, calm, energetic, etc.
3️⃣ *Processed Dataset*
- merged_emotion_audio_features.csv → Final dataset after merging all features & labels.

----

## 🛠️ Installation & Setup
1️⃣ *Clone the Repository*
git clone https://github.com/YOUR_GITHUB_USERNAME/emotion-music-ml.git
cd emotion-music-ml

2️⃣ *Create a Virtual Environment*
python -m venv env
source env/bin/activate  # On macOS/Linux
env\Scripts\activate  # On Windows

3️⃣ *Install Dependencies*
pip install -r requirements.txt

----
