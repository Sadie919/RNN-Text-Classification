# 🧠 RNN Text Classification 

This project applies deep learning models to classify news articles into multiple categories. 
Two recurrent neural network architectures — **Simple RNN** and **Bidirectional LSTM (BiLSTM)** 

## 📊 Dataset

The dataset contains news articles labeled by topic.

**Target Classes**

Sport, Business, Politics, Tech, Entertainment  

## 🤖 Models

- **Simple RNN**  
- **Bidirectional LSTM (BiLSTM)**  

## ⚙️ Workflow

Text preprocessing → Tokenization → Sequence padding → Embedding layer → Model training → Validation monitoring → Test evaluation → Confusion matrix analysis → Model comparison

## 📈 Evaluation

Performance is measured on a held-out test set using:
Accuracy, Precision, Recall, F1 Score, Confusion Matrices  

## 🎯 Key Takeaways

- **BiLSTM significantly outperforms Simple RNN** (~94% vs ~63% accuracy)  
- LSTM’s memory mechanism helps capture long-range word dependencies  
- Simple RNN struggles with overlapping vocabulary between categories  
- Remaining errors mainly occur in the **Tech** category due to mixed terminology

## 💻 Code & Notebook

You can review the full project code in the shared notebook or run it directly in Google Colab:

👉 **[Open the notebook in Google Colab]([https://colab.research.google.com/drive/19CQD77hhdDeVHjF2KKHolZAtcfkbhXva?usp=sharing]**
