# 📩 SMS Spam Detection Using TensorFlow

## 📘 Introduction  
This project focuses on detecting spam messages through text classification using machine learning. Built with Python and libraries such as TensorFlow, Scikit-learn, pandas, NumPy, Seaborn, and Matplotlib, the project explores various approaches to accurately classify SMS messages as spam or ham (non-spam).

## 🎯 Project Objective  
The goal of this project is to implement and compare different machine learning models for spam detection. It aims to help users understand which models are most effective for text classification tasks involving short messages.

## 🔍 Features  
- **Data Preprocessing**: Load and clean the SMS dataset for model training.  
- **Data Visualization**: Analyze and visualize patterns in spam and ham messages.  
- **Model Development**: Implement multiple models including:
  - Naive Bayes  
  - Neural Networks with custom word embeddings  
  - Bidirectional LSTM  
  - Transfer Learning with Universal Sentence Encoder  
- **Model Evaluation**: Evaluate each model using standard metrics like Accuracy, Precision, Recall, and F1-score.  
- **Model Comparison**: Visualize and compare the performance of all models.

## 🛠️ How to Use  

### ⚙️ Prerequisites  
Make sure Python and the required libraries are installed. You can install dependencies using:

```bash
pip install -r requirements.txt
```

### 🚀 Steps to Run  
1. Clone the repository and navigate to the project folder.  
2. Download the `spam.csv` dataset and place it in the appropriate directory.  
3. Run the Jupyter notebook or Python scripts in order.  
4. Review the performance metrics and plots to compare models.

## 📊 Project Workflow  

### 1️⃣ Data Loading and Preprocessing  
- Load `spam.csv` using pandas.  
- Clean the dataset by removing unused columns, renaming fields, and encoding labels (spam = 1, ham = 0).

### 2️⃣ Data Exploration and Visualization  
- Visualize class distribution (spam vs. ham).  
- Analyze message lengths and other text statistics.

### 3️⃣ Model Development  
Build and train the following models:
- **Naive Bayes**  
- **Neural Network with custom embeddings**  
- **Bidirectional LSTM**  
- **Transfer Learning using Universal Sentence Encoder**

### 4️⃣ Model Evaluation  
Evaluate each model using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- Classification Report

### 5️⃣ Model Comparison  
- Compare results visually using bar charts.  
- Analyze trade-offs between precision and recall for each model.

## 📈 Model Results Overview  

### 🔹 Naive Bayes  
- **Accuracy**: X%  
- **Precision**: X%, **Recall**: X%, **F1-Score**: X%  
- **Explanation**: A simple probabilistic model that works well for text classification, despite assuming feature independence.

### 🔹 Neural Network with Custom Embeddings  
- **Accuracy**: X%  
- **Precision**: X%, **Recall**: X%, **F1-Score**: X%  
- **Architecture**: Embedding layer → LSTM → Dropout → Dense layers  
- **Explanation**: Learns word embeddings and sequence patterns but requires more training time.

### 🔹 Bidirectional LSTM  
- **Accuracy**: X%  
- **Precision**: X%, **Recall**: X%, **F1-Score**: X%  
- **Explanation**: Processes sequences in both directions to capture deeper context and improve classification performance.

### 🔹 Transfer Learning (Universal Sentence Encoder)  
- **Accuracy**: X%  
- **Precision**: X%, **Recall**: X%, **F1-Score**: X%  
- **Explanation**: Leverages pre-trained sentence embeddings to extract semantic meaning from text, enabling strong performance with fewer data.

## 📊 Model Performance Comparison  
- **Accuracy Comparison**: Which model performs best overall.  
- **Precision vs. Recall**: Trade-off analysis for each model.  
- **F1-Score Analysis**: Combined metric for balanced evaluation.

## ✅ Conclusion  
This SMS Spam Detection project offers a complete workflow for building, evaluating, and comparing machine learning models for text classification. It’s a valuable resource for understanding NLP workflows and deploying practical spam detection systems using modern ML techniques.