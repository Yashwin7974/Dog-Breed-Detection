 Dog Breed Classification using Deep Learning

About the Project

This project is a deep learning based system that can recognize dog breeds from images. It uses the Stanford Dogs Dataset, which contains 120 different breeds, making it a challenging classification task due to the visual similarities between many breeds.
A pretrained MobileNetV2 model is used with transfer learning so the system can learn useful features without training from scratch. When a user uploads a dog image, the model analyzes it and predicts the most likely breed along with a confidence score.


Features:
* Detects dog breed from an input image
* Supports 120 different dog breeds
* Uses transfer learning for improved performance
* Applies data augmentation to reduce overfitting
* Shows predicted breed with confidence score
* Generates confusion matrix for evaluation
* Allows real-time image upload for prediction

Tech Stack:
* Python
* TensorFlow / Keras
* MobileNetV2
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab

Dataset:
The model is trained using the Stanford Dogs Dataset which contains over 20,000 images across 120 dog breeds. This dataset is widely used for fine-grained image classification tasks.

How to Run:
1. Install the required libraries in the code.
2. Upload your Kaggle API key file (`kaggle.json`).
3. Download the dataset using the Kaggle API.
4. Run the training code.
5. Fine-tune the model for better performance.
6. Upload a dog image when prompted.
7. The model will predict the breed along with confidence score.

Model Training:
* MobileNetV2 is used as the base pretrained model.
* In Phase 1, only the new classification layers are trained.
* In Phase 2, selected layers of the base model are unfrozen and fine-tuned.

Evaluation:-
Model performance is evaluated using:
* Accuracy
* Classification Report
* Normalized Confusion Matrix

