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
| `distilbert_emotion_inference_and_eval.ipynb`    | Loads the fine-tuned model and runs inference using a Gradio UI.|

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

## 🏋️ Fine-Tuning Summary

- Trained for 3 epochs
- Final training loss: ~0.13
- Saved final model and tokenizer to `./emotion-distilbert`

---

## 🤝 Contribution & Learning Goal

This is a **learning project** — feel free to fork or use as a reference if you're also exploring how to fine-tune NLP models. The main goal is to understand each step in the pipeline, from data preprocessing to saving and using a fine-tuned model.

---

## 📬 Contact

Made with 🚀 by **Okoth**  
GitHub: [Okoth67](https://github.com/Okoth67)
