# ✨ Next Word Predictor of a Sentence

A Natural Language Processing (NLP) project that predicts the **most likely next word** in a sentence using language modeling techniques.  
This can be extended to build autocomplete features, chatbots, or intelligent writing assistants.

---

## 🚀 Features
- Predicts the next word given a partial sentence
- Supports multiple models:
  - **N-gram Language Model** (simple baseline)
  - **LSTM / RNN** (deep learning approach)
- Trained on large text corpus for better accuracy
- Exposed via **FastAPI** for easy integration
- Can be extended into an autocomplete or text generator

---

## 🛠️ Tech Stack
- **Python 3**
- **FastAPI** (for serving predictions)
- **TensorFlow / Keras** or **PyTorch** (for deep learning models)
- **NLTK / SpaCy** (for preprocessing)
- **Uvicorn** (server)

---

## 📂 Project Structure
- Next-Word-Predictor/
- ├── # Training dataset (text corpus)
- ├── # Jupyter notebooks for training & experiments
- │── main.py # FastAPI app entrypoint
- │── model.h5 # Trained deep learning model
- │─ tokenizer.pkl # Saved tokenizer
- ├── requirements.txt # Dependencies
- └── README.md # Documentation
