# AI-Image-Captioning-System

An AI-powered full-stack web application that generates contextual captions for uploaded images using the BLIP Transformer model from Hugging Face.

---

## 🚀 Features

- Upload images from your device
- Generate AI-based image captions
- Real-time caption generation
- Responsive modern UI
- React frontend + Flask backend
- Transformer-based image understanding
- REST API integration

---

## 🛠️ Tech Stack

### Frontend
- ReactJS
- CSS
- Axios

### Backend
- Flask
- Flask-CORS
- Python

### AI / ML
- Hugging Face Transformers
- BLIP Image Captioning Model
- PyTorch
- Pillow

---

## 📂 Project Structure

```bash
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


🧠 How It Works
User uploads an image through the React frontend
Frontend sends image to Flask backend
BLIP Transformer model processes image
AI generates contextual caption
Backend sends generated caption back to frontend
Frontend displays caption to user

