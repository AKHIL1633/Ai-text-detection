# 🧠 AI vs Human Text Classification

This project focuses on distinguishing between human-written and AI-generated text using two different approaches:

### 🔹 1. BERT + XGBoost Pipeline
- Extracted contextual embeddings using BERT (CLS token).
- Used XGBoost classifier for binary classification.
- Fast and effective for small to medium datasets.

### 🔹 2. Hybrid Deep Learning Model (LSTM + Transformer + CNN)
- Applied n-gram vectorization and integer encoding.
- Used Bidirectional LSTM for sequential learning.
- Integrated Transformer block for attention and Conv1D for local pattern detection.
- Achieved high generalization on unseen GPT-3 and ChatGPT samples.

### 📊 Metrics Compared
- Accuracy
- Precision, Recall, F1-Score
- Generalization performance on different AI models

### 📁 Dataset
Used a public Kaggle dataset containing human and AI-generated text samples from GPT-3 and ChatGPT.

---

## 🧪 How to Run
Clone the repo and run:

```bash
# For BERT + XGBoost
cd BERT_XGBoost
python xgboost_classifier.py

# For Hybrid Model
cd Hybrid_LSTM_CNN
python training_script.py


| Model           | Accuracy | Precision | Recall | F1-Score | Notes                       |
| --------------- | -------- | --------- | ------ | -------- | --------------------------- |
| BERT + XGBoost  | 96.4%    | 0.95      | 0.96   | 0.96     | Strong baseline             |
| Hybrid LSTM+CNN | 98.6%    | 0.98      | 0.99   | 0.98     | Best generalization overall |


