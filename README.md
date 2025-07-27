Convolutional Neural Network-based Grape Leaf Disease Detection With Regional Language Integration
This is a deep learning–powered web application that identifies grape leaf diseases from uploaded images. It uses a trained Convolutional Neural Network (CNN) and is served via a Flask web interface.

🔍 The model predicts one of the following four classes:

✅ Healthy

🍂 Black Measles Disease

🍇 Black Rot Disease

🌿 Leaf Blight Disease

🚀 Demo
Upload a photo of a grape leaf and the system will classify it into one of the above categories.

📁 Project Structure

GrapeDiseaseDetection/
├── app.py                       # Flask backend
├── grape_disease_classifier.h5  # Trained Keras model
├── static/
│   └── image3.jpeg              # Background image
├── templates/
│   └── index.html               # Web UI template
├── .gitignore                   # Git ignore rules
├── README.md                    # Project documentation


⚙️ How to Run the Project

Clone the Repository:
git clone https://github.com/your-username/GrapeDiseaseDetection.git
cd GrapeDiseaseDetection

(Optional) Create a virtual environment:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Run the Flask app:
python app.py

Open in your browser:
http://127.0.0.1:5000/

🧠 Model Info
Framework: TensorFlow / Keras

Input Size: 224 × 224 × 3

Output: 4-class classification

Format: .h5 Keras model

📂 Dataset
The dataset used for training is available here:
📎https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
You can find the database of the diseases related to Grape plant in the above link.

🧰 Requirements

Main libraries:

Flask

TensorFlow

Keras

NumPy

Pillow
