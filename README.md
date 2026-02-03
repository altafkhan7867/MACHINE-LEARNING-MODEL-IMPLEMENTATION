COMPANY: CODTECH IT SOLUTIONS 
NAME: ALTAF KHAN
INTERN ID: CTIS0967 
DOMAIN: Python Programming
DURATION: 6 Weeks
MENTOR: Neela Santhosh Kumar

# SMS Spam Detection Model

A machine learning project that classifies SMS messages as spam or legitimate using scikit-learn and Naive Bayes algorithm.

## Overview

This project implements a text classification system using TF-IDF vectorization and Multinomial Naive Bayes to detect spam messages with high accuracy. The model is trained on 5,574 SMS messages and includes comprehensive evaluation metrics.

## Features

- 📊 Complete data preprocessing and exploratory analysis
- 🤖 Multiple ML algorithms (Naive Bayes, Logistic Regression, Random Forest)
- 📈 Performance visualization (confusion matrix, ROC curve, feature importance)
- 🧪 Custom message testing capability
- 💾 Model persistence for deployment

## Installation

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Open and run the Jupyter notebook:
```bash
jupyter notebook spam_detection_model.ipynb
```

Run cells sequentially to:
1. Load and explore the SMS dataset
2. Preprocess and vectorize text data
3. Train the classification model
4. Evaluate performance with visualizations
5. Test with custom messages

## Model Performance

- **Algorithm**: Multinomial Naive Bayes
- **Feature Extraction**: TF-IDF (3000 features)
- **Accuracy**: ~97%+ on test set
- **Dataset**: SMS Spam Collection (5,574 messages)

## Project Structure

```
.
├── spam_detection_model.ipynb    # Main Jupyter notebook
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

## Technologies Used

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## 👨‍💻 Author

**Altaf Khan**
- GitHub: [@altafkhan7867](https://github.com/altafkhan7867)
- Email: altafliyakatkhan@gmail.com

## License

Open source - feel free to use and modify for learning purposes.
