# 🎧 Urban Sound Classification using CNN

## 📌 Project Overview

This project builds a **Deep Learning model (CNN)** to classify urban sounds such as **siren, dog bark, drilling, car horn, and more** using audio data.

Audio signals are converted into **MFCC (Mel-frequency cepstral coefficients)** and fed into a **Convolutional Neural Network (CNN)** for classification.

---

## 🚀 Features

* 🎵 Classifies real-world urban sounds
* 🧠 Uses CNN for audio classification
* 🔊 Supports `.wav` audio input
* ⚡ Built using Google Colab
* 📊 Achieves ~80–90% accuracy

---

## 📂 Dataset

Dataset used: **UrbanSound8K**

* 8,732 labeled audio clips
* 10 sound classes:

  * Air conditioner
  * Car horn
  * Children playing
  * Dog bark
  * Drilling
  * Engine idling
  * Gun shot
  * Jackhammer
  * Siren
  * Street music

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Librosa
* NumPy, Pandas
* Scikit-learn

---

## ⚙️ How It Works

1. Load audio dataset
2. Convert audio → MFCC features
3. Normalize and preprocess data
4. Train CNN model
5. Predict sound class

---

## 🧠 Model Architecture

* Conv2D (32 filters) + MaxPooling
* Conv2D (64 filters) + MaxPooling
* Conv2D (128 filters) + MaxPooling
* Dense Layer (256 neurons)
* Dropout (0.4)
* Output Layer (Softmax)

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Upload dataset or use Kaggle API
3. Run all cells step-by-step
4. Upload audio file for prediction

---

## 🎧 Sample Output

```text
Input: car_horn.wav  
Output: car_horn
```

---

## ⚠️ Limitations

* Similar sounds may be misclassified
* Accuracy depends on audio quality
* Not 100% accurate for random real-world noise

---

## 📈 Future Improvements

* Use CRNN (CNN + LSTM)
* Use pretrained models like YAMNet
* Real-time sound detection 🎤

---

## 👨‍💻 Author

THARUN C

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!


