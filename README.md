**Sign Language Digit Recognition 🤟**

A deep learning-based project that recognizes American Sign Language (ASL) digits (0–9) in real-time using Convolutional Neural Networks (CNN) and OpenCV. Achieved 96% accuracy with efficient preprocessing and a responsive prediction pipeline.

**🔗 Dataset Source**

Sign Language Digits Dataset by Arda Mavi
The dataset contains 2062 labeled grayscale images of hand signs representing digits 0–9.

**🚀 Features**

Real-time digit recognition from webcam input
Achieves ~96% accuracy on test data
Preprocessing techniques like ROI extraction, resizing, and grayscale normalization
Live prediction using a trained CNN model (Keras/TensorFlow)

🛠️ Tech Stack

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

**🧠 Model Architecture**

Input Layer (64x64 grayscale images)

Convolutional + ReLU + MaxPooling Layers

Fully Connected Dense Layers

Softmax Output Layer (10 classes)

**⚙️ How to Run**

Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/sign-language-digit-recognition.git
cd sign-language-digit-recognition

Install dependencies
pip install -r requirements.txt
Train the model (or use the pre-trained model)
python train_model.py

Run real-time recognition
python detect_gesture.py


**📊 Results**

Accuracy: 96% on test data
Latency: Near-instant predictions with webcam input
Noise Reduction: Improved image quality via preprocessing (~35% noise reduction)

**📚 Use Cases**

Assistive technology for the hearing/speech impaired
Real-time educational tools for learning sign language
Gesture-based human-computer interaction systems
