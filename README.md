# AI vs Human Review Detector

AI vs Human Review Detector is a Machine Learning web application that analyzes product reviews and predicts whether the review is AI-generated or written by a human. The project uses Natural Language Processing (NLP) techniques along with a Logistic Regression model to classify reviews.

## Features

- Detects AI-generated vs Human-written reviews
- Text preprocessing and NLP pipeline
- Sentiment analysis using VADER
- TF-IDF vectorization for text feature extraction
- Logistic Regression based classification model
- Interactive web interface for analyzing reviews
- REST API built using Flask

## Tech Stack

- Python
- Flask
- HTML
- CSS
- JavaScript
- Scikit-learn
- spaCy
- NLTK
- VADER Sentiment

## Project Structure


AI-Review-Detector
│
├── app.py
├── train_model.py
├── README.md
│
├── models
│ ├── scaling_pipeline.pkl
│ ├── vectorization_pipeline.pkl
│ └── Review_classifier_LG.pkl
│
├── templates
│ └── index.html
│
└── static
├── style.css
└── script.js


## Installation

1. Clone the repository


git clone https://github.com/yourusername/AI-Review-Detector.git


2. Navigate to the project folder


cd AI-Review-Detector


3. Install required libraries


pip install flask flask-cors pandas numpy nltk spacy vaderSentiment joblib scikit-learn


4. Download spaCy model


python -m spacy download en_core_web_sm


5. Run the application


python app.py


6. Open in browser


http://127.0.0.1:5000


## How It Works

1. User enters a product review in the web interface.
2. The review text is preprocessed using NLP techniques.
3. TF-IDF vectorization converts text into numerical features.
4. Additional features like sentiment score and review length are extracted.
5. The trained Logistic Regression model predicts whether the review is AI-generated or human-written.
6. The result is displayed instantly on the UI.

## Future Improvements

- Add review analytics dashboard
- Improve model accuracy with larger datasets
- Add user authentication
- Store analyzed reviews in a database
- Deploy the application on cloud platforms

## Author

Aman Bhardwaj
