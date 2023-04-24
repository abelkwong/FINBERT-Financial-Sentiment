# FinBERT Sentiment Analysis
This project provides sentiment analysis for financial news using the FinBERT model, which is a pre-trained BERT language model fine-tuned on financial data. The sentiment analysis is based on a three-class classification system: positive, negative, and neutral.

## Requirements
- Python 3.6 or later
- PyTorch 1.2.0 or later
- Transformers 3.1.0 or later
- Pandas
- Matplotlib

## Installation
Clone this repository:
```
git clone https://github.com/abelkwong/finbert-sentiment-analysis.git
```

Install the required packages:
```
pip install -r requirements.txt
```

## Usage
To perform sentiment analysis on a single financial news article, run the predict.py script:
```
python predict.py --article "The stock market rose today after positive earnings reports from several major companies."
```
To perform sentiment analysis on multiple financial news articles, provide a CSV file containing the articles in a text column, and run the batch_predict.py script:
```
python batch_predict.py --csv_file news_articles.csv
```

## Results
The output of the sentiment analysis will be printed to the console and saved to a CSV file.

## License
This project is licensed under the [MIT License](https://github.com/abelkwong/logr-breast-cancer/blob/main/LICENSE).

## Acknowledgments
The FinBERT model was developed by [Prosus AI](https://github.com/ProsusAI/finBERT).
