# Fake News Detection with Machine Learning 📰

Welcome to the **Fake News Detection** project! This project focuses on classifying news articles as either "fake" or "true" using machine learning models. The dataset consists of news articles labeled as fake or true, and the goal is to build a model that can accurately classify new articles. The project uses **scikit-learn** for building and evaluating machine learning models.

---

## Features

- **Text Preprocessing**: Uses `CountVectorizer` and `TfidfVectorizer` for converting text into numerical features.
- **Model Training**: Trains multiple machine learning models, including K-Nearest Neighbors, Random Forest, and Naive Bayes.
- **Model Evaluation**: Evaluates models using classification reports.

---

## How It Works

1. **Data Loading**: Load the dataset containing news articles and their labels (fake or true).
2. **Text Preprocessing**: Convert the text data into numerical features using `CountVectorizer` and `TfidfVectorizer`.
3. **Model Training**: Train machine learning models on the processed data.
4. **Model Evaluation**: Evaluate the models using classification reports.

---

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.8 or higher
- pandas
- numpy
- scikit-learn
- spacy

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download spaCy model**:
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. **Run the script**:
   ```bash
   python fake_news_detection.py
   ```

---

## Results

### Model Performance

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| K-Nearest Neighbors    | 0.73     | 0.84      | 0.73   | 0.75     |
| Random Forest          | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| Naive Bayes            | 0.XX     | 0.XX      | 0.XX   | 0.XX     |

### Classification Report

The classification report provides a detailed breakdown of the model's performance, including precision, recall, and F1-score for each category.

---

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [scikit-learn](https://scikit-learn.org/) for machine learning models and evaluation.
- [pandas](https://pandas.pydata.org/) for data manipulation.
- [numpy](https://numpy.org/) for numerical computations.
- [spaCy](https://spacy.io/) for text preprocessing.

---

Detect fake news with ease using this Fake News Detection project! 🚀📊
