```markdown
# **AICTE Project**
## **Fitness Tracker – Calorie Burn Prediction System**

---

## **1. Project Overview**
This project is a **Machine Learning-based Fitness Tracker** that predicts the number of **calories burned** during exercise based on user physiological and workout parameters.

The system uses structured health data to build a regression model that estimates calorie expenditure accurately.

---

## **2. Dataset Description**

The project uses two CSV datasets:

### **1. exercise.csv**
Contains user physical and workout-related features:

- **User_ID** – Unique identifier  
- **Gender** – Male/Female  
- **Age** – Age of the user  
- **Height** – Height (cm)  
- **Weight** – Weight (kg)  
- **Duration** – Exercise duration (minutes)  
- **Heart_Rate** – Heart rate during exercise  
- **Body_Temp** – Body temperature  

### **2. calories.csv**
Contains target variable:

- **User_ID** – Unique identifier  
- **Calories** – Calories burned  

Both datasets are merged using **User_ID** for model training.

---

## **3. Technologies Used**
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Jupyter Notebook**
- **Streamlit (app.py for deployment)**

---

## **4. Project Structure**
```

AICTE/
│── app.py
│── fitness_tracker.ipynb
│── exercise.csv
│── calories.csv
│── README.md
│── .git/

```

---

## **5. Methodology**
1. **Data Loading**
2. **Merging datasets using User_ID**
3. **Data Preprocessing**
4. **Feature Selection**
5. **Model Training (Regression Model)**
6. **Model Evaluation**
7. **Deployment using Streamlit**

---

## **6. How to Run**

### **Step 1: Install Dependencies**
```

pip install -r requirements.txt

```

### **Step 2: Run Jupyter Notebook (Optional – Model Training)**
```

jupyter notebook fitness_tracker.ipynb

```

### **Step 3: Run the Web Application**
```

streamlit run app.py

```

---

## **7. Objective**
- Predict calories burned during exercise  
- Provide data-driven fitness insights  
- Build a deployable ML-based health application  

---

## **8. Future Enhancements**
- Add real-time wearable device integration  
- Improve model using advanced regression algorithms  
- Deploy on cloud platforms (AWS/Render/Heroku)  
- Add user authentication and history tracking  
```
