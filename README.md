# Naan-Mudhalvan-Project-
fake-news-detection-nlp/
│
├── 📁 data/
│   └── fake_or_real_news.csv          # Dataset (add .gitignore for large files)
│
├── 📁 notebooks/
│   └── 01_Exploratory_Analysis.ipynb  # EDA and preprocessing steps
│   └── 02_Model_Training.ipynb        # Model training and evaluation
│
├── 📁 models/
│   └── rf_model.pkl                   # Trained Random Forest model
│   └── tfidf_vectorizer.pkl          # Trained TF-IDF vectorizer
│
├── 📁 app/
│   └── app.py                         # Streamlit application
│   └── requirements.txt              # Dependencies for deployment
│
├── 📁 images/
│   └── confusion_matrix.png          # Visual outputs for README
│   └── wordclouds.png
│
├── .gitignore                        # Ignore model files, virtual env, large datasets
├── README.md                         # Project overview, setup instructions
├── LICENSE                           # License info (optional)
└── environment.yml                   # Optional conda environment file
