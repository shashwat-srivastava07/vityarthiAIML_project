# vityarthiAIML_project
#  Emotion Detector CLI App

A Simple AI/ML-based Emotion Detection Command Line Application developed using Python and Scikit-learn.
This project will predict the emotion behind the user’s input text and keep a record of the predictions.

---

##  Project Overview

Emotion Detector CLI Application:
This is a Command Line Interface Application that takes a text input from the user and uses a Machine Learning model to predict the emotion behind the input.

###  Supported Emotions
 Joy 😊, Sadness 😢Anger, 😡, Fear 😨, Love ❤️, Surprise 😲

---

##  Features

The Emotion Detector CLI App allows a user to input a specific sentence and then predict the emotion behind that sentence. The user can input any sentence, and the machine learning model will predict the emotion behind that sentence. In addition to this, the user can also see the confidence level of the predicted emotion. The program also offers useful features, such as viewing the history of previous predictions, clearing the history, and viewing the help menu, making this a very useful and user-friendly application.

---

##  Technologies Used

This project is developed using **Python** as the programming language. It also utilizes significant libraries that are used in machine learning. The project uses **Pandas** for reading and handling the data. It also uses **Scikit-learn** for building the machine learning pipeline. For feature extraction on text data, it uses **TF-IDF Vectorization**. For classification, it uses the **Logistic Regression** algorithm. The model is saved using **Pickle**. This way, the application is able to reuse the trained model instead of training it every time. It also uses regular expressions (**re module** for cleaning the input text.

##  Project Structure

```bash
EMOTION_DETECTOR_CLI/
│
├── app.py                  # Main CLI application
├── train.py                # Model training script
├── dataset.csv             # Training dataset
├── history.txt             # Stores prediction history
├── README.md               # Project documentation
├── requirements.txt        # Required Python libraries
│
└── model/
    └── emotion_model.pkl   # Saved trained model
