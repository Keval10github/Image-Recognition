#   KEVAL RAVANI 

# 🌟 Image Recognition with CIFAR-10 Dataset 🌟

## ![CIFAR-10]

![Image](https://github.com/user-attachments/assets/15f7a7e9-e270-42c3-8759-8b72186cd557)
---

## **📜 Overview**
Welcome to the **Image Recognition Project** by **Keval Ravani**! 🚀  
This project uses a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset**, which contains 60,000 32x32 color images across 10 classes, such as 🛩️ airplanes, 🚗 automobiles, 🐦 birds, 🐱 cats, and more.

---

## **📂 Project Structure**
The project follows a well-defined pipeline:
1. **Dataset Loading**: CIFAR-10 dataset is loaded using TensorFlow.
2. **Preprocessing**: Images are normalized for better model performance.
3. **Model Construction**: A CNN is built using TensorFlow/Keras.
4. **Training**: The model is trained on the dataset.
5. **Evaluation**: The model's accuracy is tested on unseen data.
6. **Visualization**: Random samples are visualized with predictions.

---

## **🎯 Features**
- 🔍 Image classification using CNNs
- 📊 Model training and evaluation
- 🖼️ Visualization of sample predictions
- 🏷️ Classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

---

## **📦 Requirements**
### Dependencies
Ensure you have the following Python libraries installed:
- `tensorflow` (compatible with Python 3.11)
- `matplotlib`
- `random`

Install them using:

### Python Version
This project requires **Python 3.11.x** for compatibility with TensorFlow.

---

## **🛠️ Installation**
1. Clone the repository:
2. Install dependencies:
3. Run the script:

---

## **📖 Code Walkthrough**

### 1️⃣ Dataset Loading and Preprocessing
The CIFAR-10 dataset is loaded and split into training and testing sets:
Images are normalized to scale pixel values between 0 and 1:

### 2️⃣ Visualization of Data Samples
Random samples from the training set are visualized with their labels:

### 3️⃣ CNN Model Architecture
The CNN consists of three convolutional layers followed by max-pooling layers and dense layers:

### 4️⃣ Training and Evaluation
The model is compiled and trained for two epochs:
Evaluation on the test set:

### 5️⃣ Prediction and Visualization of Results
Random samples from the test set are visualized with their actual and predicted labels:

---

## **📊 Results**
| Metric            | Value |
|--------------------|-------|
| Training Accuracy | ~59%  |
| Test Accuracy     | ~60%  |

### Sample Output Visualization:
#### Actual Label: 🐸 Frog  
#### Predicted Label: 🐸 Frog  
![Image](https://github.com/user-attachments/assets/92d74173-4893-40cb-b862-e5e632461fc6)
---

## **📈 Future Enhancements**
- Train the model for more epochs to improve accuracy.
- Experiment with data augmentation techniques.
- Implement transfer learning using pre-trained models like ResNet or VGG.

---

## **👨‍💻 Author**
**Keval Ravani**  
💌 Email: kevalravani06@gmail.com  
📅 Date: April 13, 2025  

---

## **📜 License**
This project is licensed under the MIT License.

---

## **✨ Acknowledgments**
Special thanks to the TensorFlow team for providing an easy-to-use framework and to the creators of the CIFAR-10 dataset.

---

## **🚀 Let's Collaborate!**
Feel free to open issues or submit pull requests for improvements. Contributions are always welcome! 😊

---

