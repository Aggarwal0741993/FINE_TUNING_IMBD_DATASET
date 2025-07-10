# 🎬 IMDB Movie Review Sentiment Classifier

This project fine-tunes a `roberta-base` transformer model to classify movie reviews from the IMDB dataset as **positive** or **negative**. The final model is deployed using **Streamlit** and hosted on **Hugging Face Spaces** for real-time prediction.

---

## 🚀 Demo

👉 [Live App on Hugging Face Spaces](https://huggingface.co/spaces/shubhamg074/imbd_movie_review_sentiments)

---

## 📌 Features

- Fine-tuned `roberta-base` on the IMDB binary sentiment classification task.
- Achieved high validation accuracy with early stopping and model evaluation.
- Interactive Streamlit web app for real-time text input and prediction.
- Confidence score displayed alongside sentiment result.
- Deployment on Hugging Face Spaces (no need for local setup).

---

## 🧠 Model Details

- **Base Model**: `roberta-base` from Hugging Face Transformers
- **Dataset**: IMDB Large Movie Review Dataset from kaggle (https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Task**: Binary classification (`positive` or `negative`)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

---

## 📂 Project Structure

. ├── app.py                   # Streamlit app file ├── requirements.txt         # Python dependencies ├── config.json              # Model config ├── model.safetensors        # Fine-tuned model weights ├── tokenizer_config.json ├── vocab.json, merges.txt   # Tokenizer files └── README.md                # Project description

---

## ⚙️ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/imdb-sentiment-roberta.git
   cd imdb-sentiment-roberta

2. Install dependencies:

pip install -r requirements.txt


3. Run the Streamlit app:

streamlit run app.py




---

🧪 Sample Inputs

Review Text	Prediction	Confidence

"This movie was absolutely fantastic!"	🟢 Positive	0.98
"Terribly written and poorly acted."	🔴 Negative	0.95



---

🛠 Tools & Libraries

transformers (Hugging Face)

PyTorch

Streamlit

Datasets (IMDB)

safetensors



---

🧾 License

This project is licensed under the MIT License.


