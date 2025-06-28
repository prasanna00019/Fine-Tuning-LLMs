# 🔧🧠 LLM Fine-Tuning 
Welcome to the **LLM Fine-Tuning Repo** — a collection of hands-on fine-tuning experiments on large language models (LLMs) like GPT-2.  
Here you'll find mini-projects that explore how fine-tuning transforms general-purpose models into task-specific experts.

---

## 🎯 What This Repo Is For

This repository is dedicated to building, training, and evaluating LLMs fine-tuned on custom datasets for various **text classification** and **language understanding** tasks.

- 🚀 Based on HuggingFace Transformers
- 📚 Fine-tuned from GPT-2 (for now) later will be doing on different models
- 🧪 Designed for experimentation, benchmarking, and learning

---

## 🧩 Current Projects

| Project | Description |
|--------|-------------|
| 📘 [`subject-classifier`](subject-classification-fine-tuning.ipynb) | Fine-tunes GPT-2 to classify academic subjects (Math, Science, History, etc.) based on input sentences |
| 😊 [`emotion-classifier`](EMOTION-CLASSIFICATION-FINE-TUNING.ipynb) | Fine-tunes GPT-2 to classify emotional tone in short texts (happy, sad, angry, etc.) |
| 📰 [`news-category-classifier`](news-classifier-fine-tuning.ipynb) | Fine-tunes GPT-2 to categorize news headlines/articles into domains like Business, Sports, Technology, etc. |

Each project has:
- ✅ A preprocessed dataset
- ✅ A training script (with HuggingFace Trainer or LoRA)
- ✅ Evaluation metrics (accuracy)
- ✅ Sample predictions
- ✅ README for reproducibility

---

## 🧠 Upcoming Fine-Tuning Projects (Planned)

Here’s what I’ll be working on soon:

| Project | Description |
|---------|-------------|
| 🧘 `spiritual-text-classifier` | Classify spiritual content (e.g., yoga, devotion, Vedanta, karma, bhakti) |
| 🏥 `medical-intent-detector` | Fine-tune a model to detect user intent in medical queries (symptom vs appointment vs emergency) |
| 📄 `legal-document-tagger` | Fine-tune a legal-specific classifier for document tagging |
| 💬 `multi-label tweet classifier` | Handle tweets with multiple tags (sarcasm, hate speech, news, personal) |
| ✍️ `style-transfer-generator` | Fine-tune an LLM to rewrite content in different tones (e.g., Shakespearean, sarcastic, formal)

---

## 🛠️ Tech Stack

- 🤗 HuggingFace Transformers
- 🧨 GPT-2 as base model(later will experiment with different models)
- 🧪 Datasets: custom + HuggingFace Datasets
- ⚙️ Training: full fine-tuning, LoRA (in future), PEFT

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/llm-finetuning-lab.git
cd llm-finetuning
pip install -r requirements.txt
