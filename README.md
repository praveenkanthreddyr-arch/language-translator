# Language Translator using Machine Learning  

This project is a **Language Translator** built with **Python and Machine Learning**. It uses a **Sequence-to-Sequence (Seq2Seq) model** with **Keras/TensorFlow** to translate sentences from **English to French**. A simple **Tkinter-based GUI** is also provided to test translations interactively.  

---

## 🚀 Features
- Train a Seq2Seq model on an English–French dataset  
- Save and load trained models  
- Translate sentences using the GUI  
- Uses **TensorFlow/Keras** for deep learning  
- Simple and lightweight GUI with **Tkinter**  

---

## 📂 Project Structure
```
language-translator-ml-codes/
│── LangTransGui.py        # GUI application for translation
│── langTraining.py        # Model training script
│── training_data.pkl      # Preprocessed training data
│── eng-french.txt         # English-French dataset
│── s2s/                   # Saved Seq2Seq model (TensorFlow/Keras format)
```

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/language-translator-ml-codes.git
   cd language-translator-ml-codes
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(If you don’t have a `requirements.txt`, install manually: `tensorflow`, `keras`, `numpy`, `pickle`, `tkinter`)*

---

## 🏋️ Training the Model
Run the training script:
```bash
python langTraining.py
```
This will train the model on `eng-french.txt` and save it inside the `s2s/` folder.

---

## 🖥️ Running the Translator GUI
After training (or using the pre-trained model in `s2s/`), run:
```bash
python LangTransGui.py
```
A window will open where you can type English sentences and get French translations.

---

## 📊 Example
**Input:**  
```
I love machine learning
```

**Output:**  
```
J'aime l'apprentissage automatique
```

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.  

---

