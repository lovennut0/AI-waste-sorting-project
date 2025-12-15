By Nutnicha Leelakornkij / ณัฐณิชา ลีลากรกิจ

This project have done during my fourth year in Bachelor's Degree as Computer Engineering student.

**Project Overview**

The AI Waste Sorting Model is a machine learning project that classifies waste images into categories such as plastic, metal, paper, glass, and dangerous waste.
The model aims to assist in automating waste segregation processes using image recognition and computer vision techniques.

**Features**

- Image Classification: Classifies waste images into predefined categories.
- Computer Vision Processing: Uses image preprocessing (resizing, normalization, augmentation) to improve accuracy.
- Model Training & Evaluation: Trained using convolutional neural networks (CNNs) with performance metrics such as accuracy and loss tracking.
- Debugging & Optimization: Experimented with hyperparameters and data augmentation for better generalization.

**How It Works**

Input waste images are loaded and preprocessed using OpenCV / TensorFlow utilities.

The CNN model extracts visual features and predicts the waste category.

The predicted label helps determine the correct disposal type (e.g., recyclable, organic).

**Technologies & Libraries**
- Python 3
- TensorFlow / Keras – for deep learning model implementation
- NumPy & Pandas – for data handling
- OpenCV / Pillow – for image preprocessing
- Matplotlib – for visualization and performance plots

**link to access the dataset**

*Waste dataset with labels*

https://kaggle.com/datasets/bad582727c1add96b094a9b55d765b5925dafe68c54d53e0bb855c7dcd54fb85

*Waste dataset no labels*

https://www.kaggle.com/datasets/marshmelloo/wastesortingdataset?utm_medium=social&utm_campaign=kaggle-dataset-share&utm_source=facebook&fbclid=IwY2xjawNuy29leHRuA2FlbQIxMQABHgSmQwlZB70IWnn0kAJVe3It1JQNQ47RgLvtEBmtfjaNs0CoSqcq29O30aMy_aem_hVofTQ-iweVjcQmVnwMHXw



**Key Learning Outcomes**
- Implemented a CNN for multi-class image classification.
- Improved model performance using preprocessing and augmentation.
- Practiced model debugging and hyperparameter tuning.
