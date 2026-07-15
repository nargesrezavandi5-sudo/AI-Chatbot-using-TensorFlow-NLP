# AI-Chatbot-using-TensorFlow-NLP
An intelligent chatbot built with Python, TensorFlow/Keras, and Natural Language Processing (NLP). The chatbot classifies user intents using a neural network trained on custom conversational data and generates appropriate responses.

## 🚀 Features

* Intent classification using Deep Learning
* Natural Language Processing with tokenization and lemmatization
* Bag-of-Words feature extraction
* Customizable intents dataset (`intents.json`)
* Trained TensorFlow/Keras model
* Interactive chatbot interface
* Easy to extend with new intents and responses

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NLTK
* NumPy
* Pickle
* JSON

## 📂 Project Structure

```text
├── chatbot.ipynb          # Model training notebook
├── test_robot.ipynb       # Chatbot testing notebook
├── chatbot_model.h5       # Trained neural network model
├── intents.json           # Dataset of intents and responses
├── words.pkl              # Saved vocabulary
└── README.md
```

## ⚙️ How It Works

1. User input is preprocessed using NLP techniques.
2. The sentence is converted into a Bag-of-Words vector.
3. The trained neural network predicts the user's intent.
4. A suitable response is selected from the corresponding intent category.

## 📊 Dataset

The chatbot is trained on a custom intent dataset containing multiple categories such as:

* Greetings
* General conversation
* Academy information
* Medical service navigation
* Blood pressure management
* Hospital search
* Pharmacy search
* Drug information

The dataset can easily be expanded by adding new intents and retraining the model.
