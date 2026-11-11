# Explainable AI Framework for Early Diabetic Retinopathy Detection

## Project Overview
This project develops an Explainable Artificial Intelligence (XAI) framework for detecting and classifying Diabetic Retinopathy (DR) using retinal fundus images.

The framework combines deep learning with visual explanation techniques to make model predictions easier to interpret.

## Dataset
- Dataset: Indian Diabetic Retinopathy Image Dataset (IDRiD)
- Training images: 413
- Testing images: 103
- Classes: 5 DR severity grades

## Technologies Used
- Python
- TensorFlow and Keras
- MobileNetV2 (CNN)
- Scikit-learn
- OpenCV
- Matplotlib and Seaborn
- Grad-CAM
- SHAP

## Implemented Features
1. Retinal image preprocessing and resizing.
2. CNN-based classification using MobileNetV2.
3. Five-class diabetic retinopathy prediction.
4. Model evaluation using accuracy, precision, recall and F1-score.
5. Confusion matrix visualization.
6. Grad-CAM visual explanations.
7. SHAP-based feature attribution.

## Initial Experimental Results
- Test accuracy: 49.51%
- Macro F1-score: 0.45
- Weighted F1-score: 0.50

These are preliminary results from the current implementation and require further improvement and validation.

## Future Work
- Vision Transformer comparison.
- Model performance improvement.
- Grad-CAM++ explanations.
- Streamlit-based user interface.
- Further explanation faithfulness and stability evaluation.

## Dataset Source
IDRiD: https://idrid.grand-challenge.org/Data/

## Disclaimer
This project is an academic research prototype and is not intended for clinical diagnosis.
