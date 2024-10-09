• Email Spam Detection using Logistic Regression •  
• Project Overview: This project aims to build a machine learning model using logistic regression to classify emails as spam or ham (not spam). The model is trained on a labeled dataset of email messages, and it uses text preprocessing and feature extraction techniques to make accurate predictions. In the final step, a predictive system is developed that can classify any new email in real-time.  

• Data Preprocessing:  
Replaced missing values in the dataset with empty strings. Performed label encoding to convert categorical labels (spam/ham) into numerical values, where spam = 0 and ham = 1.  

• Feature Extraction:  
Used the TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer to convert the text data (email messages) into numerical form, which is required for machine learning models.  

• Model Training & Evaluation:  
Split the dataset into training and test sets for model evaluation. Trained a Logistic Regression model on the training data. Evaluated the model on both the training and test data to ensure generalization, achieving similar accuracy on both sets.  

• Predictive System:  
Developed a real-time predictive system that classifies new emails as either spam or ham based on the trained model.  

• Technologies Used:  
Python   
Pandas  
Scikit-learn (for logistic regression, label encoding, and TF-IDF vectorization)  

• Results:  
The model achieved strong accuracy on both the training and test sets, demonstrating its ability to generalize well on unseen data.  
