# SMS-Spam-Detection
This repository contains a machine learning project for **SMS Spam Detection**. It uses natural language processing (NLP) and machine learning techniques to classify SMS messages as either **Spam** or **Not Spam**. A web interface is built using **Gradio** to make the model user-friendly and accessible.

# Overview
The goal of this project is to build an automated system to detect spam messages using machine learning. The system preprocesses the text data, applies TF-IDF vectorization, and trains a **Naive Bayes** classifier for message classification.

A simple and intuitive **Gradio** interface is provided for users to input messages and see real-time predictions.

# Features
- **Text Preprocessing**: Tokenization, stopword removal, stemming, and vectorization using TF-IDF.
- **Machine Learning**: Trained on Bernoulli **Naive Bayes** for binary classification.
- **User-Friendly Interface**: Gradio-based web app for interactive message testing.
- **Efficient Model**: Lightweight and fast, suitable for deployment.

# Dataset
The model was trained on the **SMS Spam Collection** dataset sourced from Kaggle and UCI Machine Learning Repository. It consists of labeled SMS messages:
- ham: Legitimate messages (non-spam)
- spam: Spam messages
The dataset was preprocessed and split into training and testing sets for model training.

# Usage
Launch the Gradio interface by running app.py.
Enter an SMS message in the text input box.
Click "Submit" to see if the message is **Spam** or **Not Spam**.

# Results
The **Bernoulli Naive Bayes** model achieved the following performance:

- **Accuracy**: 98%
- **Precision**: 97%
- **Recall**: 95%
- **F1-Score**: 96%

# Future Improvements
- Add real-time spam message detection for messaging platforms.
- Explore advanced models like **BERT** or deep learning for improved accuracy.
- Include multilingual support for SMS messages.
- Integrate user feedback for adaptive learning.

# Technologies Used
- **Python**: Programming language
- **Gradio**: Web interface framework
- **Scikit-learn**: Machine learning library
- **NLTK**: Text preprocessing library
- **TF-IDF**: Text vectorization technique

# Credits
- **Developer**: Sanket Madane
- **Guide**: Dr. Pallawi Bulakh
- **Dataset Source**:
    - Kaggle SMS Spam Collection
    - UCI Machine Learning Repository

