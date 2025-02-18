# Automated Classification and Instance Segmentation of Brain Tumors in MRI Scans

## Overview

This project focuses on developing an automated system for the detection and segmentation of brain tumors in MRI scans. Utilizing advanced machine learning techniques, our model aims to improve diagnostic accuracy and efficiency in clinical settings.

## Background

Brain tumors significantly impact patient survival rates, with nearly 70% of malignant cases resulting in mortality. Effective diagnostic methodologies, such as MRI scans, are essential for accurate tumor detection and management. Our project introduces an automated approach that enhances the efficiency of reviewing MRI scans, reducing the burden on healthcare professionals.

## Project Goals

- **Automated Detection**: Implementing machine learning models to classify and segment brain tumors in MRI images.
- **Hybrid Approach**: Combining classification and instance segmentation models to improve performance.
- **User-Friendly Reporting**: Generating detailed reports for clinicians that include segmentation results and diagnostic predictions.

## Methodology

### Machine Learning Tasks
1. **Classification**: Determine the category of brain tumors (Healthy, Glioma, Meningioma, Pituitary).
2. **Instance Segmentation**: Accurately delineate tumor boundaries in MRI images.

### Models Used
- **Convolutional Neural Network (CNN)**
- **ResNet50 + CNN**
- **Vision Transformer (ViT)**
- **U-Net for Segmentation**

### Datasets
- **Classification Dataset**: 7,023 MRI images categorized into tumor and non-tumor classes.
- **Segmentation Dataset**: 4,462 annotated images for precise tumor delineation.

## Results

The CNN model without preprocessing achieved the highest performance metrics, showcasing its effectiveness in directly extracting features from the dataset. The ViT model showed improved accuracy with specific preprocessing techniques.

## Future Work

Future research will explore alternative feature fusion techniques and the incorporation of additional imaging modalities to enhance the model's capabilities.

## Computing Resources

The project was executed on Google Colab Pro, utilizing the A100 GPU. Key libraries used include:
- Keras
- TensorFlow
- NumPy
- Pandas
- OpenCV

## Conclusion

This project demonstrates the potential of automated systems in enhancing the diagnostic process for brain tumors, ultimately aiming to improve patient outcomes through timely and accurate detection.

## Contact

For further inquiries, please reach out to the authors via their respective email addresses.