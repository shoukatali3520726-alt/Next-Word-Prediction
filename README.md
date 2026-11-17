# 🧠 Next Word Prediction Using LSTM

A Deep Learning-based Next Word Prediction application built using **Python, TensorFlow, LSTM, NLP, and Streamlit**.

This application predicts the next word based on the text entered by the user using a trained LSTM model.

## 🚀 Project Overview

Next Word Prediction is a Natural Language Processing (NLP) application that uses a Long Short-Term Memory (LSTM) neural network to predict the next word in a given sentence.

The application provides a simple and interactive web interface built with Streamlit.

Users can enter a sentence and receive a predicted next word.

## ✨ Features

- Predicts the next word from user input.
- Uses an LSTM-based Deep Learning model.
- Processes text using a trained Tokenizer.
- Applies sequence padding for consistent input length.
- Interactive Streamlit web interface.
- Loads pre-trained model and saved resources.
- Uses caching to avoid repeatedly loading model resources.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Streamlit
- Pickle
- Natural Language Processing (NLP)
- Long Short-Term Memory (LSTM)

## 📂 Project Structure

```text
Next-Word-Prediction/
│
├── app.py
├── Untitled6.ipynb
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── README.md
└── .gitignore
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/shoukatali3520726-alt/Next-Word-Prediction.git
```

### 2. Navigate to Project Directory

```bash
cd Next-Word-Prediction
```

### 3. Install Required Libraries

```bash
pip install streamlit numpy tensorflow
```

### 4. Run the Application

```bash
streamlit run app.py
```

## 💡 How It Works

1. User enters a sentence in the Streamlit interface.
2. The saved Tokenizer converts text into numerical sequences.
3. The input sequence is padded to the required length.
4. The trained LSTM model processes the sequence.
5. The model predicts the next word.
6. The predicted word is displayed on the screen.

## 📦 Required Model Files

The following files are required to run the application:

| File | Purpose |
|---|---|
| `lstm_model.h5` | Trained LSTM model |
| `tokenizer.pkl` | Saved text tokenizer |
| `max_len.pkl` | Maximum sequence length |

## 👨‍💻 Author

**Shoukat Ali**

Aspiring AI / Machine Learning Engineer

GitHub: [@shoukatali3520726-alt](https://github.com/shoukatali3520726-alt)

---

⭐ If you find this project interesting, consider giving it a star!

**Built with Python, Deep Learning & NLP.**