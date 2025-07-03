
# Tech Brand Twitter Sentiment Analysis

This project analyzes synthetic Twitter data related to major tech brands (Apple, Samsung, Google, Microsoft) to understand user sentiment trends over time.

## Features

- Synthetic data generation simulating tweets with sentiments (Positive, Negative, Neutral)
- Analysis of tweet counts per brand and sentiment
- Animated visualizations using Plotly to explore trends by month, brand, and sentiment
- Includes animated line charts and grouped bar charts for clear temporal insights

## Installation

Make sure you have Python 3.7+ installed.

Install required packages using:

```bash
pip install -r requirements.txt
```

## Usage

Run the Python script to generate data and display interactive charts:

```bash
python sentiment_analysis.py
```

You will see animated charts opening in your default web browser.

## Project Structure

- `sentiment_analysis.py` — Main script with data generation, analysis, and visualization
- `requirements.txt` — Python dependencies
- `fake_tweets.csv` — Generated synthetic dataset (optional)

## Future Improvements

- Integrate with real Twitter API data
- Add sentiment analysis from tweet text
- Build interactive dashboards using Dash or Streamlit

## License

MIT License

---

Feel free to contribute or raise issues!
