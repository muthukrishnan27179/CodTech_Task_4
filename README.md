# Task4
Spam Classifier Using Naive Bayes

🧠 About the Task This project is part of CodTech Internship Task 4: developing a machine learning-based spam classifier using Naive Bayes. The system detects whether an SMS message is spam or ham (not spam) based on training data and text vectorization.

🧰 Technologies Used CountVectorizer – for converting text to vector format

Multinomial Naive Bayes – for classification scikit-learn – for ML operations matplotlib & seaborn – for visualization (confusion matrix)

📥 Input The classifier takes SMS messages and predicts whether each message is:

Spam – unwanted/promo Ham – safe/normal message The model is trained using a labeled dataset (spam_data.csv).

⚙️ How It Works Loads and preprocesses labeled SMS data Converts text into numerical format using CountVectorizer Trains a Naive Bayes model on the training set Predicts spam or ham on test data Evaluates the model with accuracy, classification report, and confusion matrix Saves visual output and metrics to files

▶️ How to Run ✅ Make sure Python is installed ✅ Install required libraries: pip install pandas scikit-learn matplotlib seaborn

📄 Output 📊 Accuracy and Classification Report printed in terminal 📈 Confusion Matrix saved as confusion_matrix.png 📃 Detailed metrics saved in classification_report.txt

✅ Completed By K.Muthukrishnan CodTech Internship – Task 4: Spam Classifier using ML
