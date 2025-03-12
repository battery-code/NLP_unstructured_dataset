# **Advanced NLP analysis of News Articles on Chicago and Illinois**

## **Project Overview**  
This project analyzes **200,000 news articles** related to "Chicago" and "Illinois" to understand:  
- The **sentiment** around these terms.  
- The **key topics** discussed in the articles.  
- Potential insights into **public perception** and policy implications.  

The analysis was done using **Natural Language Processing (NLP) techniques**, including **Topic Modeling (LDA), TF-IDF, Sentiment Analysis, and Named Entity Recognition (NER).**  

---

## **Project Steps**  

### **1. Data Preprocessing & Exploratory Data Analysis (EDA)**  
- Cleaned and tokenized **200K news articles** (removed stopwords, URLs, punctuation).  
- Analyzed **word distributions, token counts, and text lengths**.  

### **2. Topic Modeling & Refinement**  
- Used **TF-IDF** (unigram, bigram, trigram models) to extract key terms and filter out irrelevant articles (e.g., sports news, TV shows).  
- Applied **Latent Dirichlet Allocation (LDA)** with **PyLDAvis** to identify dominant topics.  
- Leveraged **multiprocessing** to optimize LDA computations and improve efficiency.  
- Identified **6 major topics** related to Chicago & Illinois using a **hybrid approach** (TF-IDF clustering + LDA).  
- Created **word clouds** to visualize key terms behind each topic.  

### **3. Sentiment Analysis**  
- Used **TextBlob** to analyze sentiment trends in articles mentioning **Chicago & Illinois**.  
- Integrated **Google Cloud NLP API** for **targeted sentiment analysis** on specific topics.  

### **4. Named Entity Recognition (NER)**  
- Used **SpaCy** to extract key **people, locations, and organizations** mentioned in articles.  

### **5. Insights & Findings**  
- **Corruption-related articles** discussed policies to reduce corruption.  
- **Crime-related articles** highlighted public safety initiatives.  
- **High property tax discussions** raised concerns for businesses and economic impact.  

---

## **Key Outcomes**  
- **Successfully implemented an end-to-end NLP pipeline on 200K news articles**.  
- Identified **6 key topics** related to Chicago & Illinois.  
- Uncovered **public sentiment** and **policy discussions** on major issues.  
- Applied **LDA, TF-IDF, Sentiment Analysis, and NER** for structured insights.  
- Integrated **Google Cloud NLP API** for advanced sentiment detection.  

---

## **Effort & Codebase**  
🕒 **~70 hours of work**  
📄 **1,500+ lines of Python code**  

