---
title: "Transfer Learning for Glaucoma Detection"
date: 2023-10-07
tags: [machine learning, deep learning, transfer learning, medical imaging, glaucoma detection]
header:
  image: "images/projects/glaucoma-detection/gd.png"
  teaser: "images/teasers/gd.jpeg"
excerpt: "Applying transfer learning techniques to detect glaucoma from retinal images."
---


This project explores the application of transfer learning techniques to develop an image-based classifier for detecting glaucoma from retinal scans. Early detection of glaucoma is crucial for preventing vision loss, making this a valuable tool in ophthalmology.

## Dataset

The project utilizes the "partitioned_by_hospital" segment of the [RIM-ONE DL](https://www.ias-iss.org/ojs/IAS/article/view/2346) dataset, which contains retinal scans categorized into "glaucoma" and "normal" classes.

## Tech Stack

- Python
- TensorFlow / Keras
- Jupyter Notebook
- NumPy
- Matplotlib
- Scikit-learn

## Key Features

1. Implementation of three pre-trained models: VGG16, ResNet50, and InceptionV3
2. Fine-tuning process for adapting models to glaucoma detection
3. Comprehensive evaluation using multiple metrics
4. Analysis of model performance and limitations

## Methodology

1. **Pre-trained Models**: VGG16, ResNet50, and InceptionV3 were selected for their strong performance in image classification tasks.

2. **Fine-tuning Process**:
   - Loaded pre-trained models with ImageNet weights
   - Froze initial convolutional layers
   - Added new fully connected layers for glaucoma classification
   - Trained modified models using Adam optimizer

3. **Evaluation Metrics**: Accuracy, Loss, Precision, Recall, and F1 score

## Results

| Model       | Accuracy | Loss   | Precision | Recall | F1 score |
|-------------|----------|--------|-----------|--------|----------|
| VGG16       | 0.6609   | 0.7347 | 0.6766    | 0.9576 | 0.7930   |
| ResNet50    | 0.6782   | 0.6837 | 0.6782    | 1.0000 | 0.8082   |
| InceptionV3 | 0.4425   | 2.4639 | 0.6235    | 0.4492 | 0.5222   |

## Key Findings

- Limited performance of pre-trained models on the glaucoma detection task
- ResNet50 slightly outperformed other models but still showed low accuracy
- Potential reasons for underperformance include dataset limitations, preprocessing challenges, and domain mismatch

## Future Directions

- Explore larger and more diverse datasets
- Develop specialized preprocessing techniques in collaboration with ophthalmologists
- Investigate alternative architectures or custom models for medical imaging
- Conduct more extensive hyperparameter tuning

## Conclusion

While the project did not achieve high accuracy, it provided valuable insights into the challenges of applying transfer learning to specialized medical imaging tasks. The findings highlight the need for further research and domain-specific adaptations to improve glaucoma detection models.

[View Project on GitHub](https://github.com/CtripleU/Formative-1_Transfer-Learning.git)