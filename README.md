# Named-Entity-Recognition-
```
# 🧠 Named Entity Recognition on News Articles

This project performs Named Entity Recognition (NER) using a BiLSTM neural network trained on a Kaggle dataset of news articles. The goal is to identify and classify named entities like Person (PER), Location (LOC), Organization (ORG), etc., from each sentence.

---

## 📁 Dataset

- Name: Entity Annotated Corpus  
- Source: https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus  
- Format: CSV (columns: Sentence #, Word, POS, Tag)  
- Tags: IOB format (e.g., B-PER, I-LOC, O)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Keras / TensorFlow
- Scikit-learn
- Matplotlib, Seaborn

---

## 📌 Project Structure

NER_News_Articles/
│
├── ner_dataset.csv              # Dataset file from Kaggle
├── ner_model.h5                 # (Optional) Saved model
├── ner_script.ipynb             # Jupyter Notebook with code
├── README.md                    # Project description

---

## 🚀 How to Run

1. Clone the repo or download the notebook  
```

git clone [https://github.com/yourusername/NER\_News\_Articles.git](https://github.com/yourusername/NER_News_Articles.git)

```

2. Install dependencies  
```

pip install pandas numpy matplotlib seaborn sklearn tensorflow keras

```

3. Download dataset from Kaggle  
Visit: https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus  
Place `ner_dataset.csv` in your working directory.

4. Run `ner_script.ipynb` in Jupyter or Google Colab.

---


## 📈 Model Architecture

- Embedding Layer  
- Bidirectional LSTM  
- TimeDistributed Dense Layer with softmax  

The model is trained on padded word sequences and outputs one tag per token.

---

## ✅ Future Enhancements

- Add CRF layer for better sequence modeling  
- Train with spaCy or BERT for comparison  
- Deploy as a web app with Streamlit or Flask

---

## 👩‍💻 Author

Speranza Deejoe  
```

Let me know if you want this as a downloadable `.md` file or if you'd like to include a project screenshot or Colab link in the README.
