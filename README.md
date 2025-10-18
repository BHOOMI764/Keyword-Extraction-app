# Keyword Extraction Django Application

<img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/bababe42-a8c4-4a47-9d80-f4a99efe7e05" />
Paragraph:-Keyword extraction is a natural language processing (NLP) technique used to automatically identify the most significant words and phrases within a given text. The main goal of keyword extraction is to determine the key topics or themes that best represent the content of a document. This process helps reduce large volumes of text into a smaller set of meaningful terms, making information retrieval, indexing, and summarization much easier. Various methods can be used for keyword extraction, ranging from simple statistical approaches such as Term Frequency–Inverse Document Frequency (TF-IDF) to more advanced algorithms like RAKE, TextRank, and BERT-based models. In practical applications, keyword extraction is widely used in search engines, content recommendation systems, sentiment analysis, and automatic tagging. By identifying the most relevant terms, it enables machines and humans to quickly understand what a document is about without reading the entire text.

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=flat-square&logo=github)](https://github.com/BHOOMI764/keyword_extraction)

## Overview
This is a Django web application that performs keyword extraction from text using TF-IDF (Term Frequency-Inverse Document Frequency) and Natural Language Processing techniques.

## Features
- **Web Interface**: Clean, modern web interface for text input
- **Keyword Extraction**: Uses TF-IDF algorithm to extract the most relevant keywords
- **NLP Processing**: Includes text preprocessing with stopword removal, lemmatization, and n-gram analysis
- **Machine Learning Models**: Pre-trained models for efficient keyword extraction

## Tech Stack
- **Backend**: Django 3.2+
- **NLP Libraries**: NLTK, scikit-learn
- **Data Processing**: pandas, numpy
- **Frontend**: HTML, CSS, JavaScript

## Project Structure
```
code/
├── mysite/                 # Django project
│   ├── mysite/            # Django settings and configuration
│   ├── polls/             # Main application
│   │   ├── templates/     # HTML templates
│   │   ├── *.pkl          # Pre-trained ML models
│   │   └── views.py       # Application logic
│   └── requirements.txt   # Python dependencies
├── dataset/               # Training data
└── Keyword_Extraction.ipynb  # Jupyter notebook for model training
```

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/BHOOMI764/keyword_extraction.git
   cd keyword_extraction
   ```

2. **Install dependencies**:
   ```bash
   cd code/mysite
   pip install -r requirements.txt
   ```

3. **Run the Django server**:
   ```bash
   python manage.py runserver
   ```

4. **Access the application**:
   Open your browser and go to `http://127.0.0.1:8000/`

## Usage

1. Enter any text in the input field
2. Click "Submit" to extract keywords
3. The application will return the top 10 most relevant keywords with their TF-IDF scores

## Model Training

The keyword extraction models are trained using:
- **Count Vectorizer**: Converts text to numerical features
- **TF-IDF Transformer**: Calculates term importance scores
- **Feature Names**: Vocabulary of processed terms

Training data includes academic papers and research documents for robust keyword extraction.

## API Endpoints

- `GET /` - Main interface
- `POST /` - Keyword extraction endpoint

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

**Bhoomi Jaiswal**
- GitHub: [@BHOOMI764](https://github.com/BHOOMI764)

## Acknowledgments

- Django framework for web development
- scikit-learn for machine learning algorithms
- NLTK for natural language processing

- Academic paper datasets for training data##
