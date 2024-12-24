
# Sentiment Analysis Web App

Welcome to the Sentiment Analyser web app project! This repository contains the code for a Flask web application that performs sentiment analysis on user-provided text. Below is an overview of the project and instructions on how to use and run the application.

Explore the Sentiment Analyzer App live: [Mood-Metric - The Sentiment Analyzer App
](https://mood-metric.streamlit.app/)

### INPUT
![Screenshot 2024-11-12 at 12 44 59 PM](https://github.com/PANWAR-MAYANK/Sentiment-Analyzer/blob/main/assets/TestCase.PNG)
### OUTPUT
![Screenshot 2024-11-12 at 12 45 51 PM](https://github.com/PANWAR-MAYANK/Sentiment-Analyzer/blob/main/assets/Result.PNG)

## Overview

The main file, `app.py`, is the Flask application that handles routes and sentiment analysis logic. The web app allows users to input text, analyzes the sentiment using the NLTK Sentiment Intensity Analyzer, and displays the result on a separate page. The project also includes HTML templates for the main and result pages, along with a CSS file for styling.

## Installation

To run the web app, make sure you have the following dependencies installed:

-   Flask
-   googletrans
-   nltk

You can install these dependencies using the following command:

```bash
pip install Flask googletrans nltk
```

## Usage

1.  Clone this repository:

```bash
git clone https://github.com/ananyamanjunath/Sentiment-Analyser.git
cd Sentiment-Analyser
```

2.  Run the Flask application:

```bash
python app.py
```

3.  Open your web browser and go to http://127.0.0.1:5000/ to access the Sentiment Analyser web app.
    
4.  Enter your text in the provided textarea, submit the form, and view the sentiment analysis result.
    

## Acknowledgments

This web app was developed using Flask, NLTK, and the Google Translate API for language detection and translation. Feel free to explore and modify the code based on your requirements.

Please note that the web app is currently set to run in debug mode. Ensure that it meets your security and deployment standards before deploying it in a production environment.
