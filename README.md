# Face-Detection-using-PCA

## Project Overview 

This Face Detection project focuses on developing a facial recognition and classification system using machine learning techniques while exploring the functionality of dimensionality reduction through PCA. The study reported results through visualizations, such as ROC curves and confusion matrices, demonstrating strong label prediction accuracy for test images. Certain models, including LDA, LR, and SVM, outperformed others, achieving high precision, recall, F1-score, and accuracy. However, some models, like KNN, showed limitations, and others had varied outcomes

### Aim

To develop a facial recognition and classification system using machine learning techniques
on the Olivetti Faces dataset.

### Objective

- Successfully implemented multiple machine learning models to achieve accurate facial classification.
- Conducted extensive experiments with PCA for dimensionality reduction and feature extraction to improve model performance and training efficiency.
- Visualized outcomes through detailed metrics including ROC curves, confusion matrices, -and classification reports to gain insights into model performance.
- Accomplished highly accurate prediction of labels for unseen test images, demonstrating the robustness of the models.

### Pipeline

The machine learning workflow typically starts with the import of necessary libraries and classifiers, followed by data exploration to understand the dataset's characteristics. Data pre-processing involved cleaning and preparing the data and splitting it into training and testing
sets. PCA was used for dimensionality reduction. Model training was the core of the process, where multiple machine learning models were trained and tested on the PCA Transformed data. Cross-validation mean scores, Precision-Recall-ROC curves, and Hyperparameter tuning helped assess model performance followed by visualizing test images with true and predicted labels establishing a standard machine learning pipeline.

### Evaluation

This project focused on Face Recognition using the Olivetti Dataset, and several exceptional achievements were observed. Firstly, PCA was employed to determine the optimal components for data representation, and it was found that around 90 components captured over 90% of the dataset's variance. This dimensionality reduction process effectively retained crucial data traits while reducing dimensions. Classifier performance evaluation revealed strong results for LDA, LR, and SVM, showcasing high precision and recall. However, certain challenges were identified, including misclassification instances, emphasizing the need for addressing feature similarity and within-class variability. In comparison to benchmark results, there is scope for improvement in machine learning and PCA implementations. Future research directions incorporate dataset expansion, investigating sources of image errors, and fine-tuning PCA or implementing CNNs to strengthen model performance.
