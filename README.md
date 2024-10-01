# 🚀 Project Highlights

### **Multilingual BERT Model**  
Utilizes `bert-base-multilingual-cased`, a pre-trained model capable of understanding and processing both **Bangla** and **English**. It is ideal for tasks requiring comprehension of Bangla text while supporting queries in English.

### **Contextual Q&A**  
The chatbot extracts answers from Bangla news articles by identifying relevant spans of text and returning meaningful answers to user queries in English. The model is trained to handle both brief and descriptive responses depending on the question.

### **Fine-Tuning on Bangla News Dataset**  
The model is fine-tuned on a dataset of articles from a **Bangla newspaper**, with **10%** of the data used for training. The dataset includes:
- **Text:** Bangla news articles
- **Date:** Publication date
- **Timestamp:** Exact time of publication

### **Kaggle Notebook Implementation**  
The project is implemented in a **Kaggle notebook**, leveraging the large dataset for training, testing, and deploying the chatbot.

---

# 🔑 Key Features

### **Multilingual Capabilities**  
Supports **English queries** while retrieving answers from **Bangla texts** using mBERT.

### **Data Preprocessing**  
Efficiently tokenizes and processes large **Bangla text datasets**, preparing them for fine-tuning BERT.

### **Q&A System**  
Fine-tuned to provide **context-aware answers**, capable of understanding the structure of both questions and the corresponding text passages.

### **Scalable**  
Designed to handle large datasets. Although **10%** of the data is used for demonstration, the system can be scaled up for larger implementations.

### **Flexible Answer Length**  
The chatbot can provide **concise** or **detailed responses** based on the complexity of the question.

---

# 🛠️ Steps to Reproduce

### **Environment Setup**  
Install the necessary libraries (`transformers`, `torch`, `pandas`) in the Kaggle environment:
```bash
!pip install transformers torch pandas
