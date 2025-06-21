# 🧠 Emotion Classification with DistilBERT

This project demonstrates how to fine-tune the `distilbert-base-uncased` transformer model from Hugging Face on the [emotion dataset](https://huggingface.co/datasets/dair-ai/emotion). The goal is to classify text into one of six human emotions: **sadness**, **joy**, **love**, **anger**, **fear**, and **surprise**.

## 🚀 Project Summary

- **Task**: Multi-class emotion classification
- **Model**: [`distilbert-base-uncased`](https://huggingface.co/distilbert-base-uncased)
- **Dataset**: [`dair-ai/emotion`](https://huggingface.co/datasets/dair-ai/emotion)
- **Library**: Hugging Face `transformers`, `datasets`, `PyTorch`

---

## 📁 Files

| File / Folder              | Description                                  |
|---------------------------|----------------------------------------------|
| `fine_tune_distilbert_emotion_classification.ipynb` | Notebook containing data loading, preprocessing, model training, and evaluation |
| `emotion-distilbert-model/`    | Directory containing the saved fine-tuned model |
| `requirements.txt`             | Python dependencies                        |
| `README.md`                    | Project description (this file)            |

---

## 📊 Dataset Details

- **Source**: [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion)
- **Languages**: English
- **Classes**: `sadness`, `joy`, `love`, `anger`, `fear`, `surprise`
- **Split**:
  - Train: 16,000 samples
  - Validation: 2,000 samples
  - Test: 2,000 samples

## ✅ Training Configuration

- **Model**: `distilbert-base-uncased`
- **Epochs**: 3
- **Batch Size**: 16
- **Learning Rate**: 2e-5
- **Evaluation Strategy**: After every epoch

---

## 🛠 How to Use

1. Clone the repository
2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Launch the notebook and follow along:
    ```bash
    jupyter notebook emotion_classification.ipynb
    ```

---

## 🤝 Contribution & Learning Goal

This is a **learning project** — feel free to fork or use as a reference if you're also exploring how to fine-tune NLP models. The main goal is to understand each step in the pipeline, from data preprocessing to saving and using a fine-tuned model.

---

## 📬 Contact

Made with 🚀 by **Okoth**  
GitHub: [Okoth67](https://github.com/Okoth67)
