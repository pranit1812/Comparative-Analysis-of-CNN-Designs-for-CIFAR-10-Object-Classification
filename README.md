# Comparative Analysis of CNN Designs for CIFAR-10 Classification

## Overview
This project undertakes a comparative analysis of various Convolutional Neural Network (CNN) architectures for object classification on the CIFAR-10 dataset. The aim is to explore the performance implications of different model designs, ranging from basic CNNs to advanced architectures like MobileNetV2.

### Author
- Pranit Sehgal - *Arizona State University* - ASU ID: 1225456193

## Experimentation

### Motivation
The motivation behind this project is to understand the impact of architectural decisions on the performance of image classification tasks within the realm of deep learning.

### Design Phases
- **Phase 1**: Basic CNN Model without pooling layers.
- **Phase 2**: Enhanced model with pooling layers for improved efficiency.
- **Phase 3**: Augmented model with dropout layers to combat overfitting.
- **Phase 4**: Implementation of MobileNetV2, a lightweight and efficient architecture.

### Framework & Tools
- **Platform**: TensorFlow on Google Colab.
- **Dataset**: CIFAR-10, split into training, validation, and testing sets.

## Results & Analysis

- **Phase 1 Accuracy**: 50.55% - Demonstrates basic feature extraction capabilities without pooling layers.
- **Phase 2 Accuracy**: 71.61% - Shows significant improvement with the introduction of pooling layers.
- **Phase 3 Accuracy**: 70.40% - Slightly reduced accuracy due to potential over-tuning of dropout layers.
- **Phase 4 Accuracy**: 60.68% - MobileNetV2's performance indicates the need for fine-tuning to achieve optimal results on CIFAR-10.

### Conclusion
The addition of pooling layers in Phase 2 yielded the best performance, underscoring the balance between model complexity and efficiency. Future work will focus on hyperparameter tuning, dropout rate optimization, and exploring deeper architectures while considering overfitting challenges.

## Getting Started

### Google Colab Notebook
Access the experiment notebook here: [Google Colab Link](https://colab.research.google.com/drive/1gyIGlzNE2OwDk6WY4ru7b513i9hZs7te?usp=sharing)

### Installation
- Ensure you have TensorFlow installed.
- Clone this repository and open the provided Google Colab notebook.

## Usage
The notebook is divided into sections corresponding to each phase of the experiment. Run each section to reproduce the results and observe the performance of different CNN architectures.

## Contributing
Contributions to improve the models, explore new architectures, or refine the existing code are welcome. Please submit pull requests or open issues to discuss potential changes.

## License
This project is open-sourced under the MIT License.

## Acknowledgments
- Arizona State University for the academic environment fostering this research.
- TensorFlow and Google Colab for the tools enabling these experiments.

## Future Directions
Future iterations will delve into advanced tuning techniques, explore the impact of different architectures on classification accuracy, and potentially combine models for enhanced performance.

## Contact
For queries or further discussion, reach out to Pranit Sehgal at pranitsehgal@gmail.com .
