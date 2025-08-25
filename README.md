ML Assignments -Github.png
**Machine Learning Assignments** repository!  
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
