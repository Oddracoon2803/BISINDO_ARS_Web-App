# BISINDO Alphabet Recognition System - Web Interface

This repository contains the frontend web interface for the BISINDO (Indonesian Sign Language) Alphabet Recognition System. This application captures camera feeds and communicates with a Machine Learning backend to detect and classify sign language gestures.

Note: This repository only hosts the web interface. The Machine Learning backend runs separately via Google Colab.

---

## How It Works
1. The frontend accesses your webcam to capture video frames in real-time.
2. The system extracts hand landmarks (keypoints) from the camera feed.
3. These coordinate points (landmarks) are sent via API requests to the Machine Learning backend.
4. The backend processes the coordinate data through the ML model and returns the predicted BISINDO alphabet.
5. The web interface displays the classification result instantly.

---

## Getting Started

To run the complete system, you need to set up both the backend and the frontend.

### Step 1: Run the Backend (Google Colab)
Before opening the web interface, you must start the ML model server:
1. Open the Google Colab Notebook
2. Run all cells to load the ML model and start the API server.

### Step 2: Run the Frontend
Open the deployed web application:
