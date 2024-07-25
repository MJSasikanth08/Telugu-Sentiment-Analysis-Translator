
# Sentiment Analysis of Telugu Text

## Overview

This project demonstrates a sentiment analysis pipeline for Telugu text using natural language processing (NLP) tools. The process involves translating Telugu text into English and then analyzing its sentiment. The code utilizes popular NLP libraries and translation services to perform these tasks.

## Components

1. **Translation**:
   - **Google Translator**: Translates Telugu text into English to facilitate sentiment analysis in a language supported by sentiment analysis models.

2. **Sentiment Analysis**:
   - **Transformers Library**: Uses a pre-trained sentiment analysis model to determine the sentiment of the translated English text.

## Installation

To set up the environment for this project, you need to install the following Python libraries:

```sh
pip install transformers googletrans==4.0.0-rc1 torch
```

## Usage

1. **Text Translation**:
   - The code uses the Google Translator API to convert Telugu text into English.

2. **Sentiment Analysis**:
   - The translated English text is processed by a sentiment analysis model to assess its sentiment.

3. **Output**:
   - The sentiment of the text is returned as an analysis result.

## Example

Given a Telugu text input, the system translates it to English and then performs sentiment analysis, outputting the sentiment score and label.

## Conclusion

This project showcases the integration of translation and sentiment analysis for non-English text, specifically Telugu. It highlights how to leverage machine learning models and translation services to analyze text data in various languages.
