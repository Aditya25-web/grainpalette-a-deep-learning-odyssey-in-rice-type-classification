# 🌾 GrainPalette
A Deep Learning Odyssey in Rice Type Classification using Transfer Learning 🚀
GrainPalette is an intelligent rice grain classifier that leverages the power of deep learning and transfer learning (MobileNetV2) to identify different rice types with high accuracy. It simplifies the process of rice variety recognition using computer vision.

📸 Preview
Upload a rice grain image → Get instant prediction with confidence levels and visual insights!
Accurate. Fast. Smart. ✅

🔍 Features
🌾 Classifies 5 rice varieties: Basmati, Arborio, Ipsala, Jasmine, and Karacadag

🤖 Built using MobileNetV2 + Transfer Learning

📊 Live confidence pie chart using Plotly

💡 Clean, responsive web UI (Flask + Bootstrap)

📂 Upload any rice image & get instant prediction

❌ Handles non-rice inputs gracefully

🧠 Model Highlights
Parameter	Value
Base Model	MobileNetV2
Accuracy (Validation)	✅ ~96%
Loss Function	Categorical CrossEntropy
Optimizer	Adam
Trainable Params	~2.2 Million

📈 The model shows steady accuracy improvement and minimal overfitting (see Training Graphs below).

📊 Training Graphs
📈 Accuracy


📉 Loss
Loss decreases consistently across epochs.

🗃️ Dataset
Rice grain image dataset with over 200+ images per class:

Basmati

Arborio

Ipsala

Jasmine

Karacadag

Data split: Training, Validation, and Testing sets.

🧰 Tech Stack
Layer	Technology
Frontend	HTML, CSS, Bootstrap
Backend	Flask (Python)
ML Model	MobileNetV2 (Keras, TensorFlow)
Image Utils	OpenCV, Pillow
Graphs	Matplotlib, Plotly
Deployment	GitHub

🚀 How to Run Locally
bash
Copy
Edit
Step 1: Clone the repository
git clone https://github.com/Aditya25-web/grainpalette-a-deep-learning-odyssey-in-rice-type-classification.git
cd grainpalette*

Step 2: Create and activate virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

Step 3: Install dependencies
pip install -r requirements.txt

Step 4: Run the app
python app.py
Then open your browser and go to:
👉 http://localhost:5000

👨‍💻 Contributors
Aditya Kunchala – Lead Developer

🌱 Future Scope
Add more rice varieties 🌾

Improve UI with more interactivity 🎨

Integrate API or mobile version 📱

Export predictions to PDF 📄
