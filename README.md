# 🎬 Movie Recommendation System

A content-based movie recommendation system that suggests similar movies based on their metadata.  
This project demonstrates the full workflow from **data preprocessing and feature engineering to model training and API deployment**.

## 🚀 Features

- Content-based movie recommendation engine
- Data preprocessing and feature engineering
- Text vectorization using CountVectorizer
- Similarity computation using cosine similarity
- Model serialization with Pickle
- Flask API for serving recommendations

## 🧠 How It Works

1. Data preprocessing and cleaning of movie metadata  
2. Feature engineering by combining important textual attributes  
3. Text vectorization using CountVectorizer  
4. Cosine similarity computation between movie vectors  
5. Model serialization using Pickle  
6. Flask API serving recommendations in real time  

## 🏗️ Project Workflow

Data Collection → Data Cleaning → Feature Engineering → Vectorization → Similarity Matrix → Model Serialization → Flask API → Movie Recommendations

## ⚙️ Tech Stack

- Python  
- Pandas  
- NumPy  
- scikit-learn  
- CountVectorizer  
- Cosine Similarity  
- Pickle  
- Flask  

## 📂 Project Structure

movie-recommendation-system  
│  
├── notebook_For_Processing.ipynb   # Data preprocessing and model training  
├── app.py                          # Flask API for recommendations  
├── model.pkl                       # Saved vectorizer/model  
├── similarity.pkl                  # Similarity matrix  
├── movies.pkl                      # Processed movie dataset  
└── README.md  

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/yourusername/movie-recommendation-system.git
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the Flask API

```
python app.py
```

## 📌 Example

Input:
```
Movie: Avatar
```

Output:
```
Recommended Movies:
- Guardians of the Galaxy
- John Carter
- Star Trek
- The Fifth Element
- Jupiter Ascending
```

## 📈 Future Improvements

- Add collaborative filtering  
- Implement deep learning–based recommendations  
- Deploy using Docker and cloud services  
- Build a web UI for users
                    

