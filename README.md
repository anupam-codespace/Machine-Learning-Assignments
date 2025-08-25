**Machine Learning Assignments** Documentations Repository!  

# [Assignment 02 ✔︎](https://github.com/anupam-codespace/Machine-Learning-Assignments/blob/f797791f67d639a448a66e68086b485631197a89/assignment2-housepriceprediction-ipynb.ipynb) 
## Housing Price Estimation through Simple Linear Regression.  

### **Description**  
This project demonstrates a Simple Linear Regression approach to predict housing prices based on the size of the house.
The goal is to establish a mathematical model that maps the relationship between house size (independent variable) and house price (dependent variable).

The assignment also involves visualizing model performance using an Epoch vs Accuracy graph and calculating performance metrics such as R² Accuracy and Average Error.

### **Dataset**
Kaggle Dataset Reference: [Housing Prices Dataset](https://www.kaggle.com/datasets/anupamsaha002/housing) 

### **Dataset includes:**
Size → Square footage of houses
Price → Price of the house in currency units

### **Kaggle Notebook**
You can view the complete implementation here:
 [🔗 My Kaggle Notebook](https://www.kaggle.com/code/anupamsaha002/assignment2-housepriceprediction-ipynb) 

### **Model Performance**
Dataset Loaded Successfully
R² Accuracy = **27.29%**
Average Error (MAE) = **1474748.13**



### **Graphs**
### 01. Accuracy vs Epoch
![Accuracy vs Epoch](https://github.com/anupam-codespace/Machine-Learning-Assignments/blob/6a9ca95b9cce1bacdf181f8fdad24900be92b2ca/Graphs%20for%20Assignments/download%20(1).png)

### 02. Actual vs Prediction (Housing Data)
![Actual vs Prediction](https://github.com/anupam-codespace/Machine-Learning-Assignments/blob/6a9ca95b9cce1bacdf181f8fdad24900be92b2ca/Graphs%20for%20Assignments/download.png)






###---

# [Assignment 01 ✔︎](https://github.com/anupam-codespace/Machine-Learning-Assignments/blob/main/Assignment%2001/Assignment_1_Digit_Recognition.ipynb) 
## Recognize a Digit using TensorFlow (CNN Implementation)  

### **Description**  
The objective of this assignment was to implement a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify handwritten digits from the **MNIST dataset**.  

The workflow included:  
- Data loading and preprocessing (normalization, one-hot encoding).  
- Designing a CNN architecture with **Conv2D**, **MaxPooling2D**, **Dropout**, and **Dense** layers.  
- Model training and evaluation.  
- Plotting **accuracy** and **loss graphs** to visualize model performance over epochs.  

---

### **Key Details**  

- **Dataset:** MNIST (28×28 grayscale digit images, digits 0–9).  
- **Model Type:** CNN with Conv2D, MaxPooling2D, Flatten, Dense, Dropout.  
- **Evaluation Metrics:** Training & validation accuracy/loss plots, final test accuracy.  
- **Final Test Accuracy:** **98.6%** (model correctly predicts ~99 out of every 100 images).  

**Important Parameters:**  
- Optimizer: `Adam`  
- Loss Function: `CategoricalCrossentropy`  
- Epochs: `10`  
- Batch Size: `128`  

**Test Case:** Classified unseen MNIST test set images.  
**Results:** High accuracy, no significant overfitting, strong generalization to unseen data.  

---

### **📂 Resources**  
📄 **Detailed Documentation:** [View Google Doc](https://docs.google.com/document/d/1yn_iTuoqq4Tn6nX2r2aioUAiaiKAdZJE_nYoRpIUrBw/edit?usp=sharing)  
