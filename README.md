# Day-4  
# 🚀 Logistic Regression on Titanic Dataset

## 📌 Objective
This project demonstrates the implementation and understanding of **Logistic Regression** to build a binary classifier that predicts whether a passenger survived the Titanic disaster based on passenger features.

---

## 🛠️ Tools & Libraries Used
- Python 3  
- Pandas – for data handling  
- Scikit-learn – for model training, preprocessing, and evaluation  
- Matplotlib – for plotting ROC curve and sigmoid function  

---

## 📂 Dataset
- Dataset used: `titanic_cleaned.csv`  
- Preprocessed and cleaned Titanic dataset.  
- Target column: `Survived` (0 = did not survive, 1 = survived)  

---

## 📈 Project Workflow

1. **Data Import & Preprocessing**  
   - Load dataset with `pd.read_csv()`  
   - Drop irrelevant columns such as `PassengerId`  
   - Convert categorical variables to numeric using `pd.get_dummies()`  
   - Split dataset into train/test sets (80/20 split)  
   - Standardize features with `StandardScaler`  

2. **Model Training**  
   - Train Logistic Regression model using `LogisticRegression()`  

3. **Model Evaluation**  
   - Predict on test set  
   - Evaluate using confusion matrix, classification report (precision, recall, F1-score), and ROC-AUC score  
   - Plot ROC curve for visualization  

4. **Threshold Tuning**  
   - Change classification threshold (e.g., from 0.5 to 0.6)  
   - Analyze how it affects confusion matrix and classification results  

5. **Sigmoid Function Visualization**  
   - Plot sigmoid curve to explain probability mapping in logistic regression  

---

## 📊 Output & Results
- ROC-AUC score: *replace with your result*  
- Precision and recall scores reported  
- Confusion matrices at default and custom thresholds displayed  
- Sigmoid function plotted for understanding model output  

---

## 📌 Conclusion
This project builds a logistic regression classifier for Titanic survival prediction. It covers key ML steps: preprocessing, training, evaluation, threshold adjustment, and visualization of logistic regression mechanics via sigmoid function.

---

M.Sathvika  
30-05-2025
