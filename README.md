# Hate-Speech-Offensive-Language
# 📖 Overview  

**Hate speech and offensive language detection** is a crucial task in **natural language processing (NLP)** to identify and mitigate harmful content online. This project aims to develop a **deep learning model** using **Long Short-Term Memory (LSTM)** to classify text into three categories:  

✅ **Hate Speech**  
✅ **Offensive Language**  
✅ **Neutral (Neither Hate nor Offensive)**  

To ensure **fairness, transparency, and interpretability**, we integrate **Explainable AI (XAI) techniques** like **SHAP and LIME** to understand the model’s decision-making process.

---

## 🎯 **Problem Statement**  

With the rise of **social media platforms**, monitoring and regulating hate speech is challenging. Existing methods either **lack accuracy, struggle with contextual understanding, or fail to provide interpretability**. The key challenges include:  

- **Complexity of language** – Hate speech can be implicit or subtle.  
- **Data Imbalance** – Some classes (e.g., Offensive Language) have fewer samples.  
- **Contextual Misinterpretation** – Some words may seem offensive but are not.  
- **Lack of Transparency** – Many AI models work as “black boxes.”  

---

## 📂 **Dataset Information**  

The dataset used consists of **tweets labeled into three categories**:  

| **Class**          | **Count** |
|--------------------|----------|
| Hate Speech       | 19,190   |
| Offensive Language | 1,430    |
| Neither          | 4,163    |

**1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-username/hate-speech-detection.git
cd hate-speech-detection
