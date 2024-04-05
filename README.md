# Breast Cancer Detection: TensorFlow to PyTorch

## Introduction
A project aimed at using machine learning for breast cancer detection through ultrasound images. Focused on overcoming dataset challenges and class imbalances.

## Dataset Overview
- **Benign Images:** 437
- **Malignant Images:** 210
- **Normal Images:** 133

## Approach & Techniques
Employed transfer learning and data augmentation (random affine transformations, horizontal flips, color jittering, resizing, normalization) to address data scarcity and imbalance.

## Model Exploration
Experimented with various architectures; selected MobileNetV2 for its residual connections and efficiency in deep learning models.

## Results & Transition
- **TensorFlow:** Initial success marred by data leakage, with post-correction accuracy at 43%.
- **PyTorch Shift:** Led to a significant improvement, achieving 84% accuracy, underscoring PyTorch's effectiveness for this task.

## Conclusion
The project highlights the critical role of data preparation, the benefits of transfer learning, and the performance differences between TensorFlow and PyTorch in medical image analysis.

