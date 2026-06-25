Insurance Claim Prediction Based on Estimation of Vehicle Damage

## Overview

This project is an AI-powered insurance claim prediction system that automates vehicle damage detection using the **YOLOv8** deep learning model. It provides a user-friendly web application where users can upload vehicle images, detect damaged regions, and assist in the insurance claim assessment process.

The application combines **React** for the frontend, **Flask** for the backend, and **YOLOv8** for computer vision to deliver a complete end-to-end solution.

---

## Features

- Vehicle damage detection using YOLOv8
- Upload vehicle images through a React web interface
- Real-time damage detection
- Flask REST API integration
- Responsive and user-friendly frontend
- AI-powered damage analysis
- End-to-end insurance claim prediction workflow

---

## Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask
- Flask-CORS

### Machine Learning & Computer Vision
- YOLOv8
- OpenCV
- NumPy
- Pandas

### Development Tools
- Visual Studio Code
- Git
- GitHub

---

## Project Structure

```
Insurance-Claim-Prediction
│
├── backend
│   ├── app.py
│   ├── best.pt
│   └── venv
│
└── frontend
    └── claim-frontend
        ├── src
        ├── public
        └── package.json
```

---

### Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install flask flask-cors pillow pandas numpy scikit-learn xgboost joblib ultralytics opencv-python matplotlib

python app.py
```

Backend runs on:

```
http://127.0.0.1:9000
```

---

### Frontend Setup

```bash
cd frontend/claim-frontend

npm install

npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## System Workflow

1. User uploads a vehicle image.
2. React sends the image to the Flask backend.
3. Flask processes the image.
4. YOLOv8 detects damaged regions.
5. Detection results are generated.
6. Flask returns the prediction to React.
7. React displays the damage analysis to the user.

---

## Future Enhancements

- Repair cost estimation
- Damage severity analysis
- Insurance fraud detection
- Cloud deployment
- Mobile application
- Multi-image damage assessment

---

Author

Jagdish Rathod

Artificial Intelligence & Machine Learning Engineering Student

**GitHub:**  
https://github.com/8296217152

## License

This project is developed for educational and academic purposes.