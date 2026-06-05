<!--
### Your Banner Image: Replace the placeholder URL with your own
-->

<p align="center">
  <img src="https://your-image-host.com/badineniharshith-banner.png" alt="AI/ML Engineer Portfolio Banner" width="100%" />
</p>

<h1 align="center">Hi 👋, I'm Harshith Badineni</h1>
<h3 align="center">Building Production-Grade AI | Computer Vision • IoT • Generative AI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/harshith-badineni-664b322b0/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/badineniharshith" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="mailto:badineniharshith.49@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
</p>

---

## 🚀 About Me

I'm an **AI/ML Engineer Intern candidate** pursuing a B.Tech in Computer Science at GITAM University, Hyderabad (Expected 2027 | CGPA: 8.22/10). I build at the intersection of **Computer Vision**, **IoT**, and **Generative AI**.

✅ **Hands-on experience**: COCO-SSD malpractice detection, ESP32-based health monitoring & gesture control (95% accuracy), and face recognition attendance (85% accuracy).

✅ **Hardware + software**: Simulated rocket trajectories at **India Space Lab** & designed CubeSat PCBs. Now looking for an AI/ML internship to contribute to production-grade systems.

✅ **Certified professional**: IIIT Hyderabad Certified AIML Professional (24-week program) + active member of Google Developer Student Clubs & Google Cloud Community.

---

## 🔭 What I'm Currently Working On
- **Deepening MLOps**: Building CI/CD pipelines for model deployment on Google Cloud Platform.
- **Edge AI**: Optimizing .pth models for ESP32-S3 to run lightweight computer vision tasks.
- **Open Source**: Contributing to policy analysis tools using LLMs with optimized token usage (~70% reduction).

---

## 🛠️ Technical Toolbox

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### AI/ML Stack
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=OpenCV&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Web & Cloud
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlebard&logoColor=white)

### Hardware & IoT
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

---

## 📂 Featured Projects — Deep Dive

### 1. **IoT-AI Health Monitor & Gesture Control System** 🫀✋
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/badineniharshith/IOT-AI-HEALTH-CARE)

> **ESP32 | Python | PyTorch (.pth) | Sensor Fusion | Cloud Dashboard**

**The Problem:** Healthcare IoT devices rarely combine biometric monitoring with assistive gesture control. Elderly or mobility-restricted users need both.

**The Solution:** A dual-function ESP32 system that:
- Streams **real-time heart rate & body temperature** to a cloud dashboard with AI-driven anomaly detection (alerts for abnormal vitals).
- Recognizes **fist open/close gestures** (binary signal 0/1) with **95% accuracy** to control lights/applications without touch.

**My Role:** Trained the gesture recognition model, exported it as `.pth` and `.h` files for edge deployment, integrated sensors (max30100, ds18b20), and built the alerting logic.

**Tech Highlight:** Achieving 95% accuracy on a resource-constrained microcontroller — balanced model size vs. latency.

---

### 2. **PolicySphere — AI Policy Impact Analyzer** 📊
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/badineniharshith) <!-- Link to actual repo if public; otherwise use your profile -->

> **Python | Flask | Google Gemini API | JavaScript | Chart.js**

**The Problem:** Government policy documents are dense and slow to analyze. Citizens and stakeholders need real-time, sector-wise impact assessments (GDP, inflation, employment) without reading 100+ pages.

**The Solution:** A full-stack web app where you paste a policy text → Gemini AI predicts economic impacts for 5 stakeholder groups (e.g., small business, labor, investors) → outputs risk scores, 4-step action plans, and downloadable reports.

**Key Achievement:** Optimized prompts to reduce Gemini token usage by **~70%**, enabling **~4,000 free API calls/day**. Designed a fallback mock-data architecture so the app stays live even if API limits are hit.

**Live Demo Ready:** Dynamic Chart.js dashboards update instantly as you switch between policies.

---

### 3. **AI Interview Malpractice Detection System** 🎥
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/badineniharshith/AI-Based-Dental-Radiograph-Analysis-System) <!-- Adjacent to resume description -->

> **COCO-SSD | Object Detection | Real-time | Flask**

**The Problem:** Remote interviews are vulnerable to cheating — hidden phones, second person in the room, tab switching, gaze deviation.

**The Solution:** Built a lightweight COCO-SSD model that runs on a candidate's browser, detecting in real-time:
- Unauthorized objects (phone, book, extra person)
- Tab switching (via blur events)
- Gaze deviation (rough heuristic using face mesh)

**Result:** Deployed for **UptoSkills Online** as an ML Engineering Intern. The system flags timestamps of suspicious behavior and reduces manual proctoring effort by ~80%.

---

### 4. **Face Recognition Attendance System** 👤✅
[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/badineniharshith/FACE-RECOGNITION-ATTENDENCE-VERSION-1)

> **OpenCV | Haar Cascade | KNN | Flask | CSV Logging**

**The Problem:** Manual roll-call wastes 10+ minutes per class and is prone to proxy attendance.

**The Solution:** A real-time system that detects faces (Haar Cascade) and identifies registered students (KNN classifier) with **85% accuracy** across varied lighting. Automatically logs timestamped attendance to CSV and announces confirmation via voice.

**What I Learned:** KNN is surprisingly effective for small face datasets — but lighting normalization is critical. Next iteration: switch to FaceNet embeddings for >95% accuracy.

---

### 5. **Machine Learning Model Suite** 📈
> **Scikit-learn | NumPy | Pandas | KNN | Decision Trees | K-Means | Regression**

A complete benchmarking suite developed during my **IIIT Hyderabad AIML certification**. Implemented and compared:
- KNN vs Decision Trees vs K-Means on real-world datasets (accuracy, precision, recall).
- End-to-end preprocessing pipelines (null handling, scaling, train/test splits).
- Regression models (linear, ridge, lasso) for housing price prediction.

**Takeaway:** No single model wins — KNN is great for small labeled data, K-Means for customer segmentation, trees for interpretability.

---

## 📈 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=badineniharshith&show_icons=true&theme=radical" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=badineniharshith&theme=radical" alt="GitHub Streak" width="48%" />
</p>

---

## 🎓 Certifications & Achievements

- **IIIT Certified AIML Professional** – iHub Data, IIIT Hyderabad (24-week program)
- **Workshop: IoT-AI for Healthcare** – Cisco Networking Academy
- **Active Member** – Google Developer Student Clubs / Google Cloud Community
- 📜 [All Certificates (badineniharshith.github.io/certificates)](https://badineniharshith.github.io/certificates)

---

## 📫 Let's Collaborate

I'm actively looking for **AI/ML Engineering internships** (Summer 2026 / Fall 2026). If you have a role where I can build production-grade computer vision, IoT, or LLM systems — let's talk.

<p align="center">
  <a href="https://www.linkedin.com/in/harshith-badineni-664b322b0/"><img src="https://img.shields.io/badge/Let's_Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/badineniharshith"><img src="https://img.shields.io/badge/See_My_Code_on_GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---
*Last updated: June 2026 — based on live resume & projects.*
