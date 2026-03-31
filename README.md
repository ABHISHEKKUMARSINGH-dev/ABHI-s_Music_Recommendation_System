# Abhi's Music Recommendation System 🎵

**Crafted by: Abhishek Kumar Singh**  
**Registration ID: 25BCE11273**

---

### 🌟 Project Overview

This is an AI-powered music recommendation system based on real-time facial expression recognition. The application uses **OpenCV** for facial detection and a deep learning **XCEPTION** model to identify your emotional state (Happy, Sad, Angry, Neutral, etc.) via your webcam.

Once an emotion is detected, the system intelligently recommends music by launching tailored YouTube search queries, ensuring the soundtrack matches your current mood perfectly.

---

### 🚀 Quick Start (Local)

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Amazingdude1525/ABHI-s-Music-Recommendation-System.git
   cd ABHI-s-Music-Recommendation-System
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```bash
   streamlit run streamlit_app.py
   ```

---

### 🌐 Cloud Deployment

The application is fully optimized for **Streamlit Cloud**. 

**Live Demo:** [Click here to open the web app](https://abhi-s-music-recommendation-system-qgp8cnzfyrnrfbecywgnav.streamlit.app/)

*Note: Ensure you allow webcam access in your browser for the emotion detection to work.*

---

### 🛠 Tech Stack

- **Python**: Core logic and integration.
- **TensorFlow / Keras**: Deep learning for emotion recognition.
- **OpenCV**: Computer vision for real-time face tracking.
- **Streamlit**: Modern web interface and cloud deployment.
- **WebRTC**: Real-time video streaming in the browser.

---

### 📂 Repository Structure

- `streamlit_app.py`: Main entry point for both Local and Cloud execution.
- `requirements.txt`: Python package dependencies.
- `packages.txt`: System-level dependencies for the cloud environment.
- `code/model/`: Contains the pre-trained neural network weights.
- `code/ui_interfaces/`: Alternative local-only versions for Desktop and CLI.

---

**© 2026 Abhishek Kumar Singh | Reg ID: 25BCE11273**
