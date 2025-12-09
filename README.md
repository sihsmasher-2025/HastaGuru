# HastaGuru (AI-Powered Bharatanatyam Mudra Recognition Platform) 

**Team Name:** SIHSMASHER 
**Problem Statement ID:** SIH25157  
**Theme:** Smart Education  

## 📖 About The Project

This project is a comprehensive web-based platform designed to digitize the learning experience of **Bharatanatyam**, one of India's oldest classical dance forms. By bridging heritage with modern technology, we aim to make cultural education accessible, interactive, and strictly validated.

The platform utilizes **Artificial Intelligence and Computer Vision** to act as a personal digital tutor. It detects hand gestures (*Hasta Mudras*) in real-time, provides instant feedback on accuracy, and guides students through a structured curriculum.

## ✨ Key Features

### 1. 🤖 AI-Powered Recognition
* **Dual Mode System:** Users can practice using a **Live Webcam** or by **Uploading Images**.
* **Real-time Feedback:** Instant analysis of hand geometry using MediaPipe to identify the mudra and provide an accuracy score.
* **Strict Validation:** A robust protocol that prevents false positives by filtering out random hand movements or incorrect gestures.

### 2. 📚 Comprehensive Mudra Dictionary
* A digital library of **Asamyuta** (Single) and **Samyuta** (Double) hastas.
* Includes high-quality reference images, Sanskrit meanings, difficulty levels, and therapeutic benefits.
* **Smart Recommendations:** Suggests similar or related mudras to help users understand subtle differences.

### 3. 🎓 Interactive Learning & Testing (New!)
* **Structured Modules:** Step-by-step practice modules guiding learners from Beginner to Advanced levels.
* **Practice & Test Modes:** Dedicated micro-services for learning specific mudras and testing your knowledge without guidance.
* **Certification:** Users receive a verifiable **Certificate of Completion** upon passing the test modules.

### 4. 👤 User Dashboard
* A central hub for tracking daily streaks, "Hours Learnt," and managing profile settings.

## 🛠️ Tech Stack

This project relies on a robust set of dependencies to manage the frontend, backend microservices, and AI processing:

* **Frontend:** HTML, CSS, JavaScript
* **Backend Frameworks:** Flask, FastAPI
* **Programming Language:** Python
* **AI & Computer Vision:** OpenCV, MediaPipe
* **Database:** Firebase

## 📂 Project Structure

The application is divided into three distinct modules, each requiring its own server instance:

1.  **Final_Project:** The core application (Landing Page, Dashboard, Main Recognition).
2.  **mudra_learning:** The dedicated module for guided learning courses.
3.  **mudra_testing:** The module for user testing and validation.

## 🚀 Installation & Setup

To run the full platform, you must run **three separate Flask/API servers in parallel** on different ports (5000, 5001, 5002).

### Prerequisites
Ensure you have Python installed. Install the required dependencies:
```bash
pip install flask fastapi uvicorn opencv-python mediapipe firebase-admin

#Step-by-Step Execution Guide
You will need to open 3 separate Command Prompt (cmd) or Terminal windows.

###Terminal 1: Run the Main Application
This starts the main platform (Landing page, Dashboard, etc.).

Bash

cd Final_Project
python app.py
# Runs on localhost:5000
After running this, copy the localhost link provided in the terminal (usually http://127.0.0.1:5000) and open it in your browser.

###Terminal 2: Run the Learning Module
This starts the guided learning service required for the "Learn" section.

Bash

cd mudra_learning
python learning_app.py
# Runs on localhost:5001

###Terminal 3: Run the Testing Module
This starts the testing service required for quizzes and certification.

Bash

cd mudra_testing
python testing_app.py
# Runs on localhost:5002
Note: Ensure all three terminals remain open and running while you use the website. If you close any terminal, that specific feature (Main Site, Learning, or Testing) will stop working.

###Step 4: While signing in, you can use sample User ID: sample@gmail.com and password : 11111111

👥 Contributors (Team SIHSMASHER)
A huge shoutout to the team for their dedication and hard work in bringing this project to life!

Riya Shahi - riyashahi079@gmail.com

Mitanshu Shah - mitanshushah27@gmail.com

Avinash Shinde - 23ce102@svitvasad.ac.in

Nityam Patel - nityam05a@gmail.com

Varun Patel - 23ce39@svitvasad.ac.in

Umang Patel - umangpatel2415@gmail.com

🔮 Future Scope

Multilingual Translation: Implementing real-time translation of course content into regional Indian languages (Hindi, Tamil, Telugu, etc.) to make learning accessible to a wider audience.

Diverse Dance Forms: Expanding the dataset and recognition models to support other Indian classical forms like Kuchipudi, Odissi, and Kathak.
