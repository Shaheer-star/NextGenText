# 🤖 NextWord AI: LSTM-Based Next Word Prediction System

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-LSTM-blue?style=for-the-badge&logo=tensorflow"/>
  <img src="https://img.shields.io/badge/NLP-Next%20Word%20Prediction-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---
<img width="1983" height="793" alt="ChatGPT Image Apr 23, 2026, 10_37_53 PM" src="https://github.com/user-attachments/assets/4de8584a-bbe6-4c9c-a703-08422d48b065" />


## 📌 About the Project

**NextWord AI** is a deep learning-based Natural Language Processing (NLP) project that predicts the next word in a sentence using an **LSTM (Long Short-Term Memory)** neural network.

The model is trained on a **custom FAQ dataset**, allowing it to learn real-world conversational patterns and contextual relationships between words.

This project demonstrates how sequence learning models can be used in:
- Smart keyboards (autocomplete systems)
- Chatbots
- Text generation systems
- AI writing assistants

---

## 🚀 Key Features

- ✨ LSTM-based sequence learning model  
- 📚 Trained on real FAQ dataset  
- 🧠 Context-aware next-word prediction  
- 📈 Accuracy improves over epochs  
- ⚡ Lightweight and easy to run  
- 🔤 Works like an AI autocomplete system  

---

## 🧠 Model Architecture

The model follows a simple yet powerful deep learning pipeline:


Embedding Layer → LSTM Layer → Dense Layer → Softmax Output


### 🔹 Workflow:
1. Input text is tokenized  
2. Converted into numerical sequences  
3. Passed through LSTM network  
4. Model predicts probability of next word  
5. Highest probability word is selected  

---

## 📊 Training Performance

| Metric              | Value            |
|---------------------|------------------|
| Initial Accuracy    | ~5%              |
| Final Accuracy      | ~94%             |
| Number of Epochs    | 100              |
| Loss Function       | Categorical Crossentropy |
| Optimizer           | Adam             |

---

## 📂 Dataset Description

The dataset is a **FAQ-based text corpus** containing structured questions and answers such as:

- Course details  
- Payment information  
- Program structure  
- Student queries  
- Administrative FAQs  

This helps the model learn **real conversational language patterns** instead of random text.

---

## ⚙️ Tech Stack

- 🐍 Python  
- 🔥 TensorFlow / Keras  
- 📊 NumPy  
- 🧠 NLP Tokenization  
- 🔁 LSTM (Recurrent Neural Network)  

---

## 🔍 Example Prediction

**Input:**

What is the course


**Output:**

fee / duration / syllabus


---

## 📈 How It Works

1. Text preprocessing (cleaning + tokenization)  
2. Sequence generation using sliding window  
3. Model training using LSTM  
4. Loss minimization using Adam optimizer  
5. Next-word prediction using Softmax probabilities  

---

## 📦 Installation

```bash
git clone https://github.com/shaheer-star/NextWord-AI.git
cd NextWord-AI
pip install -r requirements.txt
▶️ Run the Project
python model.py
📌 Requirements
tensorflow
numpy
pandas
keras
matplotlib
🚀 Future Improvements
🌐 Deploy using Streamlit / Flask web app
🔥 Use Beam Search for better predictions
📚 Train on larger dataset
🧠 Use Bidirectional LSTM
📱 Mobile-friendly deployment
🤝 Contribution

Contributions are welcome!
You can improve:

Dataset size
Model architecture
Deployment system
UI/UX of application
📧 Contact
Email: shaheerabbas414@gmail.com
GitHub: https://github.com/shaheer-star
⭐ Support

If you like this project, don’t forget to ⭐ the repository on GitHub!


Just tell me 👍
