# 🤗 Transformers & Hugging Face — Practical Implementation

A hands-on implementation of Transformer models for sentiment classification using Hugging Face. Covers pre-trained pipelines, BERT tokenization, and fine-tuning on movie review data.

---

## 🎯 Objective
- Use Hugging Face pipeline for sentiment analysis
- Understand BERT tokenization and special tokens
- Fine-tune BERT for binary sentiment classification
- Evaluate using Accuracy and F1-score

---

## 📂 Project Structure
```
transformers-huggingface-bert-sentiment/
│
├── Transformers_HuggingFace_BERT.ipynb     # Main Jupyter Notebook
├── movie_reviews.csv                        # Dataset (500 samples)
└── README.md
```

---

## 📊 Dataset
- **Source:** IMDb Movie Reviews / Synthetic
- **Size:** 500 samples
- **Labels:** Positive (1), Negative (0)
- **Split:** 80% train / 20% test

---

## 🔧 Tech Stack
- Python 3.10
- PyTorch
- Transformers (Hugging Face)
- Scikit-learn
- Matplotlib, Seaborn

---

## 🧠 Parts Covered

| Part | Description |
|------|-------------|
| Part A | Hugging Face sentiment pipeline — 5 custom sentences |
| Part B | BERT tokenization — input_ids, attention_mask, [CLS], [SEP] |
| Part C | Fine-tuning bert-base-uncased for sentiment classification |
| Part D | Confusion matrix, metrics, pipeline vs fine-tuned comparison |

---

## 📉 Results

| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Pre-trained Pipeline | 100.00% | 1.0000 |
| Fine-tuned BERT | 100.00% | 1.0000 |

> Note: Both models achieved 100% due to the synthetic dataset containing repeated patterns. Real-world performance would differ on diverse unseen data.

---

## 💡 Key Concepts Covered
- Hugging Face pipeline API
- WordPiece tokenization
- Role of [CLS] and [SEP] tokens
- BERT fine-tuning with AdamW optimizer
- Confusion matrix and classification report
- Why Transformers outperform RNNs
- What is self-attention

---

## 🚀 How to Run

**Option 1 — Google Colab (Recommended)**

Open notebook in Colab and run all cells.

**Option 2 — Local**
```bash
git clone https://github.com/TheAhmadYousaf/transformers-huggingface-bert-sentiment.git
cd transformers-huggingface-bert-sentiment
pip install transformers datasets torch scikit-learn seaborn matplotlib
jupyter notebook Transformers_HuggingFace_BERT.ipynb
```

---

## 👤 Author
**Ahmad Yousaf**
BS Artificial Intelligence
