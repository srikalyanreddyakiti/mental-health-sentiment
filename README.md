# mental-health-sentiment
A machine learning-based sentiment classification system to monitor mental health using TF-IDF, SMOTE, and classifiers like Random Forest and SVM.

This project leverages **machine learning and NLP** to classify text statements into various mental health categories such as Anxiety, Depression, Stress, Bipolar, and more. It aims to assist in early detection of mental health issues through sentiment analysis of written expressions.

## 📁 Project Structure  
- `Da final project.ipynb` – Main Jupyter notebook with full implementation  
- `Data.csv` – Dataset containing text statements and mental health labels  
- `DA Final Project.pdf` – Presentation slides summarizing the project  
- `da Final Report.pdf` – Full technical report with results and methodology  
- `README.md` – This documentation file  

## 🧠 Mental Health Categories  
- Anxiety  
- Bipolar  
- Depression  
- Normal  
- Personality Disorder  
- Stress  
- Suicidal  

## 🧪 Methodology  
1. **Preprocessing**: Text cleaning, lemmatization, stop word removal  
2. **Vectorization**: TF-IDF with unigrams and bigrams  
3. **Balancing**: SMOTE to handle class imbalance  
4. **Modeling**:  
   - Logistic Regression  
   - Random Forest (best performing with ~90% accuracy)  
   - Support Vector Machine  
5. **Evaluation**: Accuracy, precision, recall, F1-score, and confusion matrix  
6. **Testing**: Real-world sentences tested for category prediction  

## 🧰 Technologies Used  
- Python  
- Jupyter Notebook  
- pandas, numpy  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- matplotlib, seaborn  

## 💡 Applications  
- Early detection tool for mental health professionals  
- Automated monitoring in therapy and support platforms  
- AI-enhanced diagnosis and patient support  

## 👨‍💻 Author  
**Sri Kalyan Reddy Akiti**  
Data Science and artificial intellignce
