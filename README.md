# 🐱🐶 Cat vs. Dog Classification using CNN

This project is a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to classify images of cats and dogs. The model is trained on the [Cats and Dogs dataset](https://www.kaggle.com/code/serkanpeldek/keras-cnn-transfer-learnings-on-cats-dogs-dataset/input).

---

## 📌 Key Features
- Built with **TensorFlow/Keras Sequential API**
- CNN with multiple convolutional and pooling layers
- Fully connected dense layers for classification
- Uses **ImageDataGenerator** for data augmentation (rescaling, shearing, zooming, horizontal flips)
- Binary classification output: **Cat / Dog**

---

## 📂 Dataset
- Dataset Source: [Kaggle Cats and Dogs Dataset](https://www.kaggle.com/code/serkanpeldek/keras-cnn-transfer-learnings-on-cats-dogs-dataset/input)  
- The dataset contains two main folders:
dataset:
│── train: cats, dogs
│── test: cats, dogs

---

## 🚀 Usage

Clone this repository or download the code.

Place your dataset in the correct directory structure (shown above).

Update the dataset paths inside the code to match your local directory.

Run the training script:

python cat_dog_cnn.py


To test with a single image, place it inside a prediction_data/ folder and update the path in the code.
