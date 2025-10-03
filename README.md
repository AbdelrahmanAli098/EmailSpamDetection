# 📧 Email Spam Detection

This project focuses on detecting spam emails using **Machine Learning** techniques. It applies text preprocessing, feature extraction, and classification models to distinguish between **spam** and **ham (legitimate)** emails.  

## 🚀 Project Overview
- **Dataset:** spam_ham_dataset.csv  
- **Goal:** Build and evaluate models that can classify emails as spam or ham.  
- **Models Used:**  
  - Multinomial Naive Bayes (MNB)  
  - Random Forest Classifier (RFC)  

## ⚙️ Workflow
1. **Data Cleaning**  
   - Removed unnecessary columns and duplicates.  

2. **Text Preprocessing**  
   - Tokenization  
   - Stopword removal  
   - Lemmatization  
   - Regex-based cleaning  

3. **Feature Extraction**  
   - Bag-of-Words with `CountVectorizer`.  

4. **Model Training & Evaluation**  
   - Split into training and test sets  
   - Trained MNB and RFC models  
   - Evaluated using Accuracy, Confusion Matrix, and Classification Report  

5. **Testing on New Samples**  
   - Evaluated models on unseen email examples (both spam and ham).  

## 📊 Results
- **Multinomial Naive Bayes (MNB):** Correctly classified 3/4 new samples.  
- **Random Forest Classifier (RFC):** Correctly classified all 4/4 new samples.  

## 📝 Conclusion
Both models achieved good accuracy, but:  
- **RFC** showed **better robustness** on unseen/ambiguous cases, making it more reliable for real-world spam detection.  
- **MNB** remains a **fast, strong baseline** for text classification tasks.  
