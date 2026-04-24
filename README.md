# CNN-ensemble-brain-tumor-MRI-classification
Brain tumor classification using CNN and ensemble deep learning models on MRI images for accurate medical image analysis.

## Project Files
Preprocessing and CNN:
https://github.com/nazeefashahzad/CNN-ensemble-brain-tumor-MRI-classification/blob/main/01_preprocessing_and_cnn.ipynb


Ensemble CNN + MobileNet:
https://github.com/nazeefashahzad/CNN-ensemble-brain-tumor-MRI-classification/blob/main/02_ensemble_cnn_mobilenet.ipynb


CNN + EfficientNetB0:
https://github.com/nazeefashahzad/CNN-ensemble-brain-tumor-MRI-classification/blob/main/03_cnn_efficientnetb0.ipynb


Ensemble CNN + VGG16:
https://github.com/nazeefashahzad/CNN-ensemble-brain-tumor-MRI-classification/blob/main/04_ensemble_cnn_vgg16.ipynb


Transfer Learning
https://github.com/nazeefashahzad/CNN-ensemble-brain-tumor-MRI-classification/blob/main/05_transfer_learning_models.ipynb


## Results & Comparative Analysis

### Model Performance

| Model                          | Accuracy | Precision | Recall | F1-Score |
|--------------------------------|----------|-----------|--------|----------|
| Custom Deep CNN                | 98.86%   | 0.99      | 0.99   | 0.99     |
| CNN + EfficientNetB0           | 97.73%   | 0.98      | 0.98   | 0.98     |
| CNN + VGG16                    | 97.54%   | 0.98      | 0.97   | 0.97     |
| CNN + MobileNet                | 96.78%   | 0.97      | 0.97   | 0.97     |
| EfficientNetB0                 | 98.48%   | 0.98      | 0.98   | 0.98     |
| MobileNet                      | 98.10%   | 0.98      | 0.98   | 0.98     |
| VGG16                          | 92.32%   | 0.92      | 0.92   | 0.92     |

---

### Key Findings

- The **custom CNN model achieved the highest accuracy (98.86%)**, outperforming all other models.
- Transfer learning models (EfficientNetB0, MobileNet) also showed strong performance.
- Ensemble models improved robustness and maintained high accuracy.
- The proposed approach demonstrates strong potential for **medical image classification tasks**.

---

### Comparison with Previous Work

| Technique                                   | Accuracy |
|--------------------------------------------|----------|
| Generic CNN                                | 81%      |
| CNN                                        | 84%      |
| VGG16 + SVM                                | 91%      |
| Custom CNN                                 | 93.3%    |
| 2D CNN                                     | 95.63%   |
| Gabor + ResNet50 + SVM                     | 95.73%   |
| Ensemble (VGG19 + InceptionV3 + ResNet10)  | 96.6%    |
| CNN + VGG16                                | 97%      |

**Our model outperforms existing approaches**, achieving higher accuracy and better classification performance.

