# GLAB 927.4.1: Hands-On Sentiment Analysis with Python

## Project Overview

This project explores Sentiment Analysis using the `TextBlob` library in Python. These Natural Language Processing (NLP) techniques are applied to real-world business scenarios such as evaluating customer satisfaction from product launch reviews, analyzing service feedback comments, and deriving actionable insights from business communications. Environment setup and dependency management are handled using modern `uv` workflows (or standard `pip` environments).

## Key Concepts

* **Sentiment Analysis:** An NLP technique used to determine the underlying emotional tone of a piece of text—classifying it as positive, neutral, or negative—to gauge customer opinions.
* **Polarity:** A continuous score ranging from `-1.0` (extremely negative) to `1.0` (extremely positive) that measures the emotional orientation of a text.
* **Subjectivity:** A continuous score ranging from `0.0` (completely objective/factual) to `1.0` (completely subjective/personal opinion) that quantifies personal bias or emotion in a statement.

## Project Structure

```text
GLAB_927_4_1/ ├── .gitignore ├── .python-version ├── pyproject.toml ├── uv.lock ├── README.md └── src/
└── glab_927_4_1/ ├── __init__.py └── sentiment_analysis.py