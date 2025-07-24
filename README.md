# Language_Detection
🗣️ Language Detection with Hashing Vectorizer & SGDClassifier
This project demonstrates a scalable approach to detecting the language of text using machine learning. It leverages HashingVectorizer for efficient text vectorization and SGDClassifier with partial_fit for incremental learning on large datasets.

🔍 Features
Detects language from text input (e.g., English, French, etc.)
Batch-wise training using partial_fit for memory efficiency
Custom batch prediction function for large test sets
Achieves 73% accuracy on test data
Supports real-time prediction via predict_language() function

🧠 Technologies Used
Python
Scikit-learn
Pandas & NumPy
Jupyter Notebook

📁 How It Works
Load and preprocess the dataset (sentences.csv)
Vectorize text using HashingVectorizer
Train SGDClassifier incrementally in batches
Predict and evaluate using custom batch prediction
Use predict_language(text) for real-time detection

📊 Sample Output
print(predict_language("Bonjour, comment ça va?"))
# Output: 'fra'

🚀 Future Enhancements
Expand language coverage
Integrate deep learning models for improved accuracy
Build a web interface for user-friendly interaction
