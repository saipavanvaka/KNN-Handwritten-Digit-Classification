# Handwritten Digit Classification using KNN

## Internship Task 10 – Machine Learning

This project was completed as part of my **Machine Learning Internship (Task 10)**.  
The goal of this task is to classify handwritten digits (0–9) using the **K-Nearest Neighbors (KNN)** algorithm and understand how distance-based classification works.

---

## 📌 Objective

The main objectives of this task are:
- To understand how KNN classifies data based on distance
- To apply feature scaling for distance-based algorithms
- To tune the value of K and analyze its impact on accuracy
- To evaluate the model using visual and numerical methods

---

## 📊 Dataset Used

**Primary Dataset:**  
- `load_digits()` from **Scikit-learn**

Dataset details:
- Contains handwritten digit images (0–9)
- Each image is of size **8×8 pixels**
- Total features per image: **64**
- Labels represent digits from 0 to 9

This dataset is suitable for learning and experimenting with KNN.

---

## 🛠 Tools & Technologies

- Python  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook (VS Code)

---

## ⚙️ Project Workflow

The following steps were followed to complete the task:

1. Loaded the digits dataset and verified the shape of features and labels  
2. Visualized sample digit images to confirm correct labeling  
3. Split the dataset into training and testing sets  
4. Applied feature scaling using `StandardScaler`  
5. Trained a KNN model with K = 3 and evaluated accuracy  
6. Tested multiple K values (3, 5, 7, 9) and stored accuracies  
7. Plotted accuracy vs K to select the best K value  
8. Generated a confusion matrix to analyze misclassified digits  
9. Displayed sample test images with predicted labels  

---

## 📈 Model Evaluation

- Accuracy was used to compare different K values
- A confusion matrix was used to identify classification errors
- The best K value was selected based on accuracy comparison

---

## 📁 Project Files

- `KNN_Digit_Classification.ipynb` – Main notebook containing full implementation  
- `README.md` – Project documentation  

All plots (Accuracy vs K and Confusion Matrix) are included inside the notebook.

---

## ✅ Final Outcome

Through this task, I gained hands-on experience in:
- Distance-based classification using KNN
- Importance of feature scaling
- Hyperparameter tuning (choosing the best K)
- Model evaluation using accuracy and confusion matrix
- Visual interpretation of classification results

This task helped me build a strong foundation in KNN and instance-based learning techniques.

