## Walk or Run Image Classification using InceptionV3 CNN

### Overview
This project aims to classify images as either "walking" or "running" by implementing a Convolutional Neural Network (CNN) based on the InceptionV3 architecture. The dataset used for training the model is sourced from Kaggle and includes images depicting individuals engaged in either walking or running activities. Additionally, Mediapipe's human pose estimation is utilized to generate a dataset featuring the locations of 33 key points within each photo.

### Dataset
The dataset used for training the model can be found on Kaggle [here](https://www.kaggle.com/datasets/huan9huan/walk-or-run). Due to Colab's data removal policy, the dataset has been stored in a Google Drive account to ensure persistence.

#### Dataset Structure
- The dataset comprises images depicting individuals walking or running.
- Mediapipe's human pose estimation was employed to extract the locations of 33 key points for each image.

### Model Architecture
The InceptionV3 CNN serves as the base model, and additional layers have been appended for classification purposes.

#### Model Customization
- **Activation Functions**: Rectified Linear Unit (ReLU) is used in the hidden layers for introducing non-linearity. The output layer employs the Softmax activation function to yield probabilities for each class.

### Usage
To replicate and run this project, follow these steps:
1. Download or clone the repository.
2. Access the dataset from the provided Kaggle link or from the stored dataset in Google Drive.
3. Set up Google Colab or any compatible Python environment with the necessary dependencies.
4. Execute the notebook file to train the model and perform image classification.

### Dependencies
- Python 3.x
- TensorFlow
- Keras
- Mediapipe
- Google Colab (or any Jupyter Notebook environment)

### License
Include details about the license for the project.

### Acknowledgements
Mention any individuals, organizations, or resources that you utilized or referenced for this project.

### Contact Information
Provide contact information if users have questions or want to contribute to the project.

