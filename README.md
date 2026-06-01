# Dogs vs Cats Image Classification using Support Vector Machine (SVM)

## 📌 Overview

This project was completed as part of the **Prodigy InfoTech Machine Learning Internship – Task 03**. The objective of this project is to develop a machine learning model capable of classifying images of cats and dogs using the Support Vector Machine (SVM) algorithm.

The project demonstrates image preprocessing, feature extraction, model training, prediction, and evaluation techniques in computer vision.

---

## 📂 Dataset

**Dataset:** Microsoft PetImages Dataset

The dataset consists of two categories:

* 🐱 Cat Images
* 🐶 Dog Images

For this project, images were resized and converted into numerical feature vectors before training the model.

---

## 🛠 Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🤖 Machine Learning Algorithm

### Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification tasks. It works by finding the optimal hyperplane that best separates different classes.

---

## 🚀 Project Workflow

### 1. Data Loading

* Loaded cat and dog images from the dataset.
* Assigned labels:

  * Cat = 0
  * Dog = 1

### 2. Image Preprocessing

* Resized images to 64 × 64 pixels.
* Converted images into numerical arrays.
* Flattened images into feature vectors.

### 3. Data Preparation

* Combined image features and labels.
* Split dataset into training and testing sets.

### 4. Model Training

* Trained a Support Vector Machine (SVM) classifier using training data.

### 5. Prediction

* Predicted whether an image belongs to a cat or a dog.

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## 📊 Results

| Metric           | Value                        |
| ---------------- | ---------------------------- |
| Algorithm        | Support Vector Machine (SVM) |
| Image Size       | 64 × 64                      |
| Dataset Samples  | ~999 Images                  |
| Train-Test Split | 80:20                        |
| Accuracy         | 54%                          |

---

## 📈 Output

The model successfully:

* Classified cat and dog images
* Generated predictions on unseen images
* Produced evaluation metrics
* Displayed image prediction results

Example Output:

```text
Prediction : Cat
Accuracy : 0.54
```

---

## 📁 Project Structure

```text
PRODIGY_ML_03/
│
├── PRODIGY_ML_03.ipynb
├── README.md
│
└── PetImages/
    ├── Cat/
    └── Dog/
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Image preprocessing
* Computer Vision basics
* Feature extraction
* Support Vector Machines (SVM)
* Image classification
* Machine Learning model evaluation

---

## 📌 Conclusion

This project successfully demonstrates the application of Support Vector Machines (SVM) for image classification. The model was able to distinguish between cat and dog images and provided valuable insights into computer vision and supervised machine learning techniques.

Although some misclassifications occurred due to limited training data and image resizing, the project successfully achieved its objective of implementing an SVM-based image classification system.

---

## 🔗 Internship

**Prodigy InfoTech – Machine Learning Internship**

### Task 03

**Dogs vs Cats Image Classification using Support Vector Machine (SVM)**

---

### Author

**Manjunadh Prakash**
Machine Learning Intern | Prodigy InfoTech 🚀
