# Intelligent-System-for-Tumor-Segmentation-and-Detection
This project presents an intelligent system for brain tumor detection and segmentation from MRI scans. Using advanced image processing techniques and machine learning algorithms, the system enhances the efficiency and accuracy of tumor diagnosis.

# Overview
The project leverages methods like Gaussian filtering, contrast enhancement, edge detection, and segmentation techniques such as Otsu's method and the Watershed algorithm. Features are extracted using Wavelet Transform, PCA, and Histogram of Oriented Gradients (HOG) and classified using ensemble techniques like Bagging and Boosting.

# Key Features
- Automated MRI-based brain tumor detection.
- Preprocessing with Gaussian filtering and CLAHE for image enhancement.
- Advanced segmentation using hybrid techniques.
- Feature extraction and classification with Random Forest and XGBoost.
- User-friendly interface for uploading MRI images and obtaining   classification results.

# Technology Stack
- Programming Language: Python
- Libraries & Frameworks: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Seaborn, Gradio
- Algorithms: Random Forest, XGBoost

  # Dataset
- Used a multi-class dataset containing four categories: glioma_tumor, meningioma_tumor, no_tumor, and pituitary_tumor.
- Path: C:\Users\Anil PC\OneDrive\Desktop\final project\final project\Dataset\archive (1)\Training.

# Results
- Model Accuracy:
Random Forest: [87%]
XGBoost: [86%]
- Visualizations:
Confusion Matrix
Accuracy Comparison Graphs
# Evaluation Metrics
Sensitivity: Measures the model's ability to identify positive cases.
Specificity: Measures the model's ability to identify negative cases.
Recall: Evaluates the true positive rate.
