# Youtube-Sentiment-Analysis
youtube_sentiment-Analysis
🎥 YouTube Comments Sentiment Analysis

📌 Project Overview

The YouTube Comments Sentiment Analysis project is a Machine Learning-based Natural Language Processing (NLP) project that analyzes comments posted on YouTube videos and identifies their sentiment.

The system classifies comments into three categories:

- Positive 😊
- Negative 😞
- Neutral 😐

This project helps understand viewers' opinions, feedback and reactions towards YouTube videos using Machine Learning techniques.

🎯 Project Objectives

- To analyze YouTube comments using Natural Language Processing.
- To clean and preprocess text data.
- To identify positive, negative and neutral comments.
- To convert text into numerical features using TF-IDF.
- To train Machine Learning classification models.
- To compare Logistic Regression and SVM algorithms.
- To evaluate model performance using different metrics.
- To predict the sentiment of new comments.

🧠 Algorithms Used

1. Logistic Regression (Main Algorithm)

Logistic Regression is a supervised Machine Learning algorithm used for classification. It predicts the sentiment category of a YouTube comment based on its text features.

Why Logistic Regression?

- Suitable for text classification.
- Works effectively with TF-IDF features.
- Supports multi-class classification.
- Provides class probability estimates.
- Easy to understand and interpret.

2. Support Vector Machine (SVM) – Comparison Algorithm

SVM is a supervised Machine Learning algorithm that separates different classes using an optimal decision boundary.

Why SVM?

- Effective for text classification.
- Handles high-dimensional text features.
- Works well with TF-IDF representations.
- Helps compare classification performance.

🛠️ Technologies Used

- Programming Language: Python
- IDE: Anaconda Spyder
- Libraries:
  - Pandas – Dataset handling.
  - NumPy – Numerical operations.
  - Scikit-learn – Machine Learning models.
  - Matplotlib – Data visualization.
  - NLTK – Text processing and sentiment analysis.
  - TF-IDF Vectorizer – Text feature extraction.

📂 Project Structure

YouTube-Comments-Sentiment-Analysis/
│
├── youtube_sentiment.py
├── README.md
└── YouTube Comments Dataset.csv

📊 Dataset Description

The project uses a YouTube Comments dataset containing text comments and their sentiment labels.

The dataset may contain:

- Comment Text
- Sentiment
- Toxicity Label
- Spam Label
- Other comment-related information

The sentiment column is used as the target variable when available.

Target Classification

- Positive – Expresses a positive opinion.
- Negative – Expresses a negative opinion.
- Neutral – Expresses neither a clearly positive nor negative opinion.

⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the YouTube comments dataset.
3. Identify the comment and sentiment columns.
4. Remove missing values.
5. Clean the text by removing URLs and unwanted characters.
6. Convert text into lowercase.
7. Apply TF-IDF vectorization.
8. Split the dataset into training and testing sets.
9. Train the Logistic Regression model.
10. Train the SVM model.
11. Predict sentiment for test comments.
12. Evaluate both models.
13. Compare model performance.
14. Display accuracy comparison graphs.
15. Generate confusion matrices.
16. Test the models using new sample comments.

🔍 Natural Language Processing (NLP)

NLP is used to process and understand human language.

The project uses the following text-processing techniques:

- Lowercase conversion.
- URL removal.
- Special character removal.
- Unwanted space removal.
- TF-IDF feature extraction.

TF-IDF

TF-IDF stands for Term Frequency–Inverse Document Frequency.

It converts text comments into numerical values so that Machine Learning algorithms can process them.

📈 Model Evaluation

The models are evaluated using:

- Accuracy: Measures the overall correctness of predictions.
- Precision: Measures how many predicted comments belong to the correct sentiment class.
- Recall: Measures how many actual comments are correctly identified.
- F1-Score: Balances precision and recall.
- Confusion Matrix: Shows correct and incorrect classifications.

📉 Visualizations

The project generates:

1. Logistic Regression and SVM Accuracy Comparison Graph.
2. Logistic Regression Confusion Matrix.
3. SVM Confusion Matrix.

These visualizations help compare the performance of both algorithms.

💻 How to Run the Project

Step 1: Install Required Libraries

pip install pandas numpy matplotlib scikit-learn nltk

Step 2: Dataset

Download or place the YouTube comments dataset in the project folder.

Step 3: Open the Python File

Open "youtube_sentiment.py" using Anaconda Spyder.

Step 4: Update Dataset Path

Update the CSV file path according to your computer.

Step 5: Run the Program

Execute the Python program and view the results.

📌 Sample Predictions

YouTube Comment| Expected Sentiment
This video is amazing!| Positive
Worst video ever.| Negative
It was okay.| Neutral

🌟 Applications

- YouTube comment analysis.
- Viewer feedback analysis.
- Social media opinion mining.
- Customer feedback analysis.
- Online content analysis.
- Understanding audience reactions.

🔮 Future Enhancements

- Develop a web-based sentiment analysis application.
- Analyze comments in multiple languages.
- Add real-time comment analysis.
- Improve sentiment classification performance.
- Create an interactive sentiment dashboard.

👩‍💻 Author

Sanjana

Artificial Intelligence and Data Science Student

🏁 Conclusion

The YouTube Comments Sentiment Analysis project demonstrates how Natural Language Processing and Machine Learning can be used to understand people's opinions from text comments.

Logistic Regression and Support Vector Machine algorithms are implemented and compared using different evaluation metrics.

This project provides practical experience in text preprocessing, TF-IDF vectorization, sentiment classification and Machine Learning model evaluation.

---

⭐ If you find this project useful, consider giving this repository a star!
