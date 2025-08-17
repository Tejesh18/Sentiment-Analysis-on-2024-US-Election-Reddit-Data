# Sentiment Analysis on 2024 US Election Reddit Data
Analyze Reddit comments using NLP to predict the potential winner of the US 2024 election

## Description

This GitHub repository contains a project that leverages Python to retrieve and analyze political comments from Reddit. The project is structured into two primary components: data retrieval and sentiment analysis. Using the PRAW library, the project efficiently pulls comments from political discussions on Reddit. These comments are then processed through NLP algorithms—specifically vaderSentiment and TextBlob—to predict whether the commenters are likely to support Donald Trump or Kamala Harris. Currently, the NLP analysis component requires further development and refinement. Contributions aimed at enhancing the NLP techniques or improving the overall accuracy of sentiment predictions are highly encouraged and appreciated.

## Usage
1. Clone the repository.
2. Run `pip3 install -r requirements.txt`.
3. Get your credentials from [Reddit](https://www.reddit.com/prefs/apps) and add them to `credentials.py`.
4. Edit `config.py`.
5. Run `python3 main.py`.

