
## **Fake News Detection Using Machine Learning**

## **1. Project Overview**
This project focuses on detecting fake news articles using Machine Learning techniques. The system classifies news content as **Real** or **Fake** based on textual features extracted from the dataset.

---

## **2. Objective**
- To build a reliable fake news classification model  
- To preprocess and analyze textual data effectively  
- To compare machine learning algorithms and select the best-performing model  

---

## **3. Technologies Used**
- **Python**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **TF-IDF Vectorization**
- **Machine Learning Algorithms (Logistic Regression / SVM / Random Forest)**

---

## **4. Dataset**
- Publicly available Fake News dataset (**CSV format**)  
- Contains labeled news articles (**Real/Fake**)  

---

## **5. Methodology**
1. **Data Collection**  
2. **Data Preprocessing** (Cleaning, Stopword Removal)  
3. **Feature Extraction** using **TF-IDF**  
4. **Model Training**  
5. **Model Evaluation** (Accuracy, Precision, Recall, F1-Score)  
6. **Model Saving** using **Pickle**  

---

## **6. Project Structure**
```

AICTE/
│── dataset/
│── models/
│── main.py
│── train.py
│── requirements.txt
│── README.md

```

---

## **7. How to Run**

### **Step 1: Install Dependencies**
```

pip install -r requirements.txt

```

### **Step 2: Train the Model**
```

python train.py

```

### **Step 3: Run the Application**
```

python main.py

```

---

## **8. Results**
The model achieves high classification accuracy on the test dataset and effectively distinguishes between **Real** and **Fake** news articles.

---


