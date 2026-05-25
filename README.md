AI-Image-Captioning-System

An AI-powered full-stack web application that generates contextual captions for uploaded images using the BLIP Transformer model from Hugging Face.

🚀 Features
Upload images from your device
Generate AI-based image captions
Real-time caption generation
Responsive modern UI
React frontend + Flask backend
Transformer-based image understanding
REST API integration
🛠️ Tech Stack
Frontend
ReactJS
CSS
Axios
Backend
Flask
Flask-CORS
Python
AI / ML
Hugging Face Transformers
BLIP Image Captioning Model
PyTorch
Pillow
📂 Project Structure
AI-Image-Captioning-System/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── App.css
│
├── .gitignore
├── README.md
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/007Ayushi/AI-Image-Captioning-System.git
cd AI-Image-Captioning-System
🔧 Backend Setup
Navigate to backend folder
cd backend
Create Virtual Environment
python -m venv .venv
Activate Virtual Environment
Windows
.venv\Scripts\activate
Install Dependencies
pip install flask flask-cors transformers torch pillow
Run Backend
python app.py

Backend runs on:

http://127.0.0.1:5000
💻 Frontend Setup
Open New Terminal

Navigate to frontend folder:

cd frontend
Install Dependencies
npm install
Run Frontend
npm start

Frontend runs on:

http://localhost:3000
🧠 How It Works
User uploads an image through the React frontend
Frontend sends image to Flask backend
BLIP Transformer model processes image
AI generates contextual caption
Backend sends generated caption back to frontend
Frontend displays caption to user
📸 Screenshots
Upload Image Interface
Clean and responsive UI
Real-time image preview
AI-generated caption display

🔗 GitHub Repository
https://github.com/007Ayushi/AI-Image-Captioning-System
👩‍💻 Author
Ayushi Gupta
GitHub: https://github.com/007Ayushi
LinkedIn: https://www.linkedin.com/in/guptaayushi7/
