🚗 Driver Drowsiness Detection

A real-time AI-powered system that detects driver drowsiness using computer vision and deep learning, and triggers an audio alert to prevent accidents. Built using Teachable Machine, deployed with OpenCV + TensorFlow/Keras, and designed to be extendable with vehicle-to-vehicle (V2V) communication for enhanced road safety.

📌 Features

🔍 Detects Drowsy vs. Non-Drowsy driver states in real time

🎵 Plays an alert sound (alert.wav / alert-109578.mp3) when drowsiness is detected

📹 Works with live webcam feed or video input

🧠 Pretrained Teachable Machine model (exported in both Keras and TensorFlow formats)

☁️ Runs on Google Colab or locally on your machine

🚦 Future Scope: Integration with V2V communication to send emergency alerts to nearby vehicles

🛠️ Tech Stack

Python

TensorFlow / Keras (model inference)

OpenCV (video feed processing)

Teachable Machine (model training)

Jupyter Notebook (implementation)

📂 Repository Structure
drowsy-detection/
│── Driver Drowsy Detection.ipynb   # Main implementation (Colab Notebook)
│── README.md                       # Project documentation
│── alert-109578.mp3                # Alert sound
│── alert.wav                       # Alternative alert sound
│── converted_keras.zip             # Teachable Machine exported (Keras model)
│── converted_savedmodel.zip        # Teachable Machine exported (TensorFlow SavedModel)

⚙️ Installation
🔹 1. Clone the repository
git clone https://github.com/KevinHarry05/drowsy-detection.git
cd drowsy-detection

🔹 2. Install dependencies
pip install tensorflow opencv-python numpy matplotlib

🔹 3. Run the Jupyter Notebook
jupyter notebook "Driver Drowsy Detection.ipynb"


(Or open in Google Colab for a ready-to-use environment)

🚀 Usage

Open the notebook in Colab or your local Jupyter environment

Load the pretrained model (converted_keras or converted_savedmodel)

Start the webcam feed

If drowsiness is detected → system plays alert sound

📊 Model Details

Trained using Google Teachable Machine on a custom dataset

Dataset categories:

Drowsy (eyes closed / head down)

Non-Drowsy (eyes open / alert face)

Model exported in Keras and TensorFlow SavedModel formats for flexible deployment

🎯 Future Scope

📡 Vehicle-to-Vehicle (V2V) communication

If driver remains unresponsive → send alerts to nearby vehicles or emergency services

📱 Mobile/Edge Deployment (TensorFlow Lite or ONNX conversion)

⚠️ Smarter detection (eye blink frequency, yawning detection, head tilt analysis)

📈 Performance improvement with larger, real-world datasets

📌 Applications

🚗 Smart Cars – prevent accidents from driver fatigue

🚚 Fleet Management – monitor truck/bus drivers in long-haul trips

🏭 Industrial Safety – detect drowsiness in operators handling heavy machinery

🚦 IoT + Road Safety – integrate with smart transport systems

🤝 Contribution

Contributions are welcome!

Fork the repo

Create a new branch (feature-xyz)

Commit changes

Submit a PR

📜 License

This project is open-source under the MIT License.

👨‍💻 Author

Kevin Harry
🚀 Passionate about AI, IoT, and Computer Vision for real-world safety applications
