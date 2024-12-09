# IMDB Movie Review Sentiment Analysis using RNN

This project utilizes a Recurrent Neural Network (RNN) for the classification of IMDB movie review sentiments. The application has been deployed locally using Streamlit, providing an interactive interface for users to analyze the sentiment of movie reviews.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Acknowledgements](#acknowledgements)

## Introduction

Sentiment analysis is a natural language processing (NLP) technique used to determine whether a piece of text is positive, negative, or neutral. This project focuses on classifying the sentiment of IMDB movie reviews using an RNN model.

## Features

- Analyze the sentiment of IMDB movie reviews
- Interactive Streamlit interface for user-friendly experience

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone git@github.com:SaritaPhD/End-to-End-Project-On-Classification-using-RNN.git
    ```

2. Navigate to the project directory:
    ```bash
    cd End-to-End-Project-On-Classification-using-RNN
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Run the Streamlit app:
    ```bash
    streamlit run main.py
    ```

## Usage

1. Open your web browser and navigate to `http://localhost:8501`.
2. Enter a movie review into the text box.
3. Click the "Classify" button to get the sentiment prediction (positive or negative).

## Model Details

- The model is an RNN designed to process sequences of text and predict the sentiment of movie reviews.
- The RNN is trained on the IMDB movie reviews dataset, which contains labeled reviews indicating whether the sentiment is positive or negative.
- The model architecture and training process are implemented using TensorFlow/Keras.



![alt text](Screenshot_imdb.png)