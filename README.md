# Sentiment Analysis using TF-IDF and Logistic Regression

## Overview

This project is a simple machine learning application that analyzes text and classifies its sentiment as **positive** or **negative**. It uses TF-IDF for text feature extraction and Logistic Regression for sentiment classification.

The model is trained on a small example dataset included in the Python file, making this project suitable for learning the basics of Natural Language Processing (NLP) and machine learning.

## Features

- Classifies text as positive or negative
- Uses TF-IDF to convert text into numerical features
- Uses Logistic Regression for classification
- Displays the predicted sentiment and estimated confidence
- Shows probabilities for both positive and negative sentiment
- Accepts multiple text inputs in an interactive terminal
- Handles empty input
- Allows users to exit using `quit` or `exit`

## Technologies Used

- Python
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Natural Language Processing (NLP)

## Project Structure

```text
Sentiment-Analysis/
└── sentiment_analysis.py
```

## Requirements

- Python 3.10 or later recommended
- pip

## Installation

1. Clone the repository or download the project files.

2. Open a terminal in the project directory.

3. Install the required library:

   ```bash
   python -m pip install scikit-learn
   ```

## How to Run

Run the following command in your terminal:

```bash
python sentiment_analysis.py
```

Enter a sentence when prompted. The program will display the predicted sentiment and its estimated probabilities.

Type `quit` or `exit` to close the application.

## Example

```text
=== Simple Sentiment Analysis ===
Enter a sentence to classify as positive or negative.
Type 'quit' to exit.

Text: I love this product
Predicted sentiment: POSITIVE
Model confidence: ...

Positive probability: ...
Negative probability: ...
```

*Note: The exact confidence and probability values depend on the trained model. The example illustrates the output format.*

## How It Works

1. **Training data:** The model uses labeled example sentences categorized as positive or negative.
2. **TF-IDF vectorization:** Text is converted into numerical features based on word importance.
3. **Model training:** Logistic Regression learns patterns from the labeled examples.
4. **Sentiment prediction:** The trained model predicts the sentiment of user-entered text.
5. **Probability estimation:** The model displays the estimated probability for each sentiment class.

## Limitations

- The model is trained on a small example dataset.
- It may perform poorly on unfamiliar words, slang, sarcasm, or complex sentences.
- It only classifies text as positive or negative; neutral sentiment is not supported.
- The displayed probabilities are estimates and do not guarantee prediction accuracy.
- The project does not evaluate performance on a separate test dataset.

## Future Improvements

- Train the model on a larger, more diverse sentiment dataset.
- Add neutral sentiment classification.
- Evaluate performance using accuracy, precision, recall, and F1-score.
- Improve handling of negation, slang, and unfamiliar expressions.
- Develop a graphical user interface or web application.

## License

This project is intended for educational and learning purposes.
