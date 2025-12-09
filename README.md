# HastaGuru

**Team Name:** SIHSmashers  
**Problem Statement ID:** SIH25157  
**Theme:** Smart Education  

![Project Banner](https://images.unsplash.com/photo-1628102379326-7d0462939462?q=80&w=2070&auto=format&fit=crop)

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

### 3. 🎓 Interactive Learning & Certification (New!)
* **Structured Modules:** Step-by-step practice modules guiding learners from Beginner to Advanced levels.
* **Test & Certify:** Users can take practical tests to verify their skills. Upon successful completion, the system generates a verifiable **Certificate of Completion**.

### 4. 👤 User Dashboard
* A central hub for tracking daily streaks, "Hours Learnt," and managing profile settings.

## 🛠️ Tech Stack

This project is built using a robust and scalable technology stack:

* **Frontend:**
  * **HTML5 & CSS3:** For structure and responsive styling.
  * **JavaScript:** For interactive UI logic and handling webcam streams.

* **Backend & API:**
  * **Python:** The core logic language.
  * **Flask / FastAPI:** Used to create high-performance REST APIs to handle model inference requests and serve the application.

* **AI & Computer Vision:**
  * **MediaPipe:** For efficient, real-time hand landmark detection and skeletal tracking.
  * **OpenCV:** For image preprocessing (grayscale, resizing, noise reduction) before analysis.

* **Database:**
  * **Firebase:** For real-time data storage, user authentication, and managing user progress.

## 🚀 Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/bharatanatyam-ai.git](https://github.com/your-username/bharatanatyam-ai.git)
    cd bharatanatyam-ai
    ```

2.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Application**
    ```bash
    # If using Flask
    python app.py
    
    # If using FastAPI
    uvicorn main:app --reload
    ```

4.  **Access the App**
    * Open your browser and go to `http://localhost:5000` (or the port specified in your console).

## 👥 Contributors (Team SIHSmashers)

A huge shoutout to the team for their dedication and hard work in bringing this project to life!

* **Riya Shahi** - *Project Lead & AI Model Optimization*
* **Mitanshu Shah** - *Full Stack Development & Certification Logic*
* **Avinash Shinde** - *Frontend Design & User Experience (UX)*
* **Nityam Patel** - *Backend Architecture & Database Management*
* **Varun Patel** - *Domain Research, Testing & Quality Assurance*
* **Umang Patel** - *System Integration & Real-time Performance Tuning*

## 🔮 Future Scope
* **Full Body Posture Correction:** Expanding computer vision to track body alignment (*Adavus*).
* **Multi-Dance Support:** Adding libraries for Kuchipudi and Odissi.
* **AR/VR Classroom:** Creating an immersive virtual environment for remote learning.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

---
*Built with ❤️ for India's Cultural Heritage.*
