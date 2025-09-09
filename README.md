# Credibility Analysis of News Data

This project focuses on detecting the credibility of news articles by classifying them as **fake** or **real** using **Bidirectional LSTM (BiLSTM)** with text vectorization techniques. It demonstrates a complete deep learning pipeline from preprocessing to evaluation.

---

## Project Overview
- Identifies whether a news article is **authentic or misleading**.  
- Uses **text preprocessing** and **sequence modeling** for feature extraction.  
- Employs a **BiLSTM model** to capture contextual patterns in text.  
- Evaluates performance with accuracy, precision, recall, F1-score, and confusion matrix.  

---

## Workflow
**A. Data Preparation**  
- Downloaded dataset from Kaggle (Fake and Real News Dataset).  
- Combined and labeled articles: **0 → Fake**, **1 → Real**.  

**B. Preprocessing**  
- Cleaned text (removal of punctuation, numbers, URLs, and stopwords).  
- Tokenized and padded sequences for uniform input length.  

**C. Model Building**  
- Embedding layer for word vector representation.  
- Bidirectional LSTM layers for capturing context from both directions.  
- Fully connected dense layers with dropout for classification.  

**D. Training**  
- Optimized using **Adam** with binary cross-entropy loss.  
- Trained for multiple epochs with monitoring of validation metrics.  

**E. Evaluation**  
- Visualized training/validation accuracy and loss.  
- Generated **classification report** (precision, recall, F1-score).  
- Plotted **confusion matrix** for performance analysis.  

**F. Model Saving**  
- Saved trained model (`.h5`) and tokenizer for reuse.  
- Enabled inference on unseen news data.  

---

## Features
- End-to-end pipeline for **credibility analysis of news articles**.  
- **BiLSTM-based deep learning approach**.  
- Text preprocessing, vectorization, and sequence modeling.  
- Performance visualization with curves and confusion matrix.  
- Ready for deployment and integration into applications.  
