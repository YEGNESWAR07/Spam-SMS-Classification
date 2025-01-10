## Spam SMS Classification Project 

This project focuses on classifying SMS messages as **spam** (unwanted promotional or fraudulent messages) or **ham** (normal, non-promotional messages). It leverages **Machine Learning** techniques to preprocess text data, extract relevant features, and train models for accurate classification.  


## Objective  
The primary goal of this project is to build a robust SMS spam detection system using **Natural Language Processing (NLP)** and **Machine Learning**. The program preprocesses text data, performs exploratory data analysis (EDA), and trains models to classify SMS messages with high accuracy.  


## **Tools and Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - Data Processing: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - NLP: `nltk`, `re`  
  - Machine Learning: `scikit-learn`  
- **Models**:  
  - Naive Bayes (`MultinomialNB`)  
  - Decision Tree (`DecisionTreeClassifier`)  


## **Key Features**  
1. **Text Preprocessing**:  
   - Removal of special characters, numbers, and stopwords.  
   - Lemmatization to reduce words to their base forms.  
2. **Feature Engineering**:  
   - Word count, presence of currency symbols, and numbers.  
   - TF-IDF vectorization for text representation.  
3. **Model Training and Evaluation**:  
   - Trained and evaluated **Naive Bayes** and **Decision Tree** models.  
   - Achieved high accuracy in classifying spam and ham messages.  
4. **Visualizations**:  
   - Count plots for spam vs. ham distribution.  
   - Confusion matrices for model performance evaluation.  


## **How to Run the Code**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/YEGNESWAR07/Spam-SMS-Classification.git  
   ```  
2. Install the required libraries:  
   ```bash  
   pip install pandas numpy matplotlib seaborn nltk scikit-learn  
   ```  
3. Download the dataset:  
   - Place the `SMSSpamCollection` file in the project directory.  
4. Run the Python script:  
   ```bash  
   python spam_sms_classification.py  
   ```  


## **Results**  
- **Naive Bayes Model**: Achieved high precision and recall for spam detection.  
- **Decision Tree Model**: Demonstrated interpretable predictions with good accuracy.  
- **Confusion Matrices**: Visualized true positives, true negatives, false positives, and false negatives for both models.  


## **Sample Predictions**  
The program can classify sample messages as spam or ham:  
- **Input**: "WINNER! You have won a lottery of $1000. Claim your prize now!"  
  **Output**: SPAM  
- **Input**: "Hey, are we still on for dinner tonight?"  
  **Output**: HAM  


## **Future Improvements**  
- Experiment with advanced models like **Random Forest**, **XGBoost**, or **Deep Learning** (e.g., LSTM).  
- Deploy the model as a web application using **Flask** or **Streamlit**.  
- Explore balancing techniques for imbalanced datasets (e.g., SMOTE).  


## **Contributing**  
Feel free to contribute to this project by:  
- Reporting issues or bugs.  
- Suggesting new features or improvements.  
- Submitting pull requests.  


## **License**  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  


## **Connect with Me**  
- **LinkedIn**: [Pallapothu Yegneswar](https://linkedin.com/in/PallapothuYegneswar)  
- **GitHub**: [YEGNESWAR07](https://github.com/YEGNESWAR07)  
- **Email**: yegneswarpallapothu.07@gmail.com  

