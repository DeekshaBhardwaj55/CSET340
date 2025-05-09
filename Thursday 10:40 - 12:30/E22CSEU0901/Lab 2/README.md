# README: Image Processing and Machine Learning on MNIST Dataset

## **Task 1: Image Processing Operations**
This task involves performing various image processing techniques, including resizing and blurring.

### **1.1 Image Resizing**
Resizing modifies the dimensions of an image, either enlarging or shrinking it while maintaining its aspect ratio. This is performed using different interpolation methods:
- **1.1.1 Linear Interpolation**
- **1.1.2 Nearest Neighbors Interpolation**
- **1.1.3 Polynomial Interpolation**

### **1.2 Image Blurring**
Blurring reduces image details, suppresses noise, and creates artistic effects. Common techniques used:
- **1.2.1 Box Blurring**
- **1.2.2 Gaussian Blurring**
- **1.2.3 Adaptive Blurring**

---

## **Task 2: Machine Learning Model and Evaluation**
### **2.1 Dataset Used: MNIST**
- The **MNIST (Modified National Institute of Standards and Technology) dataset** consists of 70,000 grayscale images (28x28 pixels) of handwritten digits (0-9).
- **Training Set:** 60,000 images with labels.
- **Test Set:** 10,000 images with labels.

### **2.2 Machine Learning Algorithms Used**
Two machine learning models are applied from the following options:
- **2.2.1 Naive Bayes (or its variants)**
- **2.2.2 Support Vector Machine (SVM) (or its variants)**
- **2.2.3 Decision Trees / Random Forest**
- **2.2.4 AdaBoost / Other Ensemble Methods**
- **2.2.5 Artificial Neural Networks (NN) (or its variants)**

The models are trained using an **80-20 train-test split** and evaluated using **K-fold Cross Validation**.

### **2.3 Performance Evaluation Metrics**
- **2.3.1 Accuracy** - Measures overall model correctness.
- **2.3.2 Precision (Positive Predictive Value)** - Indicates the proportion of true positives among predicted positives.
- **2.3.3 Recall (Sensitivity)** - Measures the model's ability to detect positive instances.
- **2.3.4 F-Measure (F1 Score)** - Harmonic mean of precision and recall.
- **2.3.5 Confusion Matrix** - Provides a summary of classification performance.
- **2.3.6 ROC (Receiver Operating Characteristic Curve)** - Shows model performance across different thresholds.
- **2.3.7 AUC (Area Under Curve)** - Represents the ability of the model to distinguish between classes.

---

## **Appendix: MNIST Dataset Overview**
- **Instances:** 70,000 images.
- **Attributes:** 784 (each representing one of the 28x28 pixels).
- **Target:** Digit (0-9) corresponding to the handwritten image.
- **Pixel Values:** Each pixel has a grayscale intensity ranging from **0 (black) to 255 (white).**
- **Data Sources:**
  - Training Set: **60,000 images** (used for model training).
  - Test Set: **10,000 images** (used for model evaluation).
  - Dataset Link: [Kaggle MNIST Dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset)

---

## **Tools and Libraries Used**
- **Scikit-learn**: Load dataset using `load_digits`.
- **PySpark**: Load dataset using `spark.read.csv()`.
- **OpenCV / PIL**: For image processing (resizing, blurring, etc.).

---

## **Submission Instructions**
Ensure that all results and evaluations are submitted as per LMS guidelines. The implementation should be documented, including:
1. Code implementation in Jupyter Notebook / Python scripts.
2. Graphs and metrics for model evaluation.
3. Observations and analysis.

---

**Author:** _Your Name_  
**Institution:** _Your Organization / University_

