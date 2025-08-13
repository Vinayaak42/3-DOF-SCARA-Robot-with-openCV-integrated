# Vision Based Quality Inspection of Medicine Packages using 3 DOF SCARA Robot

![SCARA Robot](images/scara_model.png)

---

## 🏷️ Badges
![Python](https://img.shields.io/badge/Python-3.9-blue)
![YOLOv5](https://img.shields.io/badge/YOLOv5-Object%20Detection-green)
![SCARA Robot](https://img.shields.io/badge/SCARA-Robot-orange)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-Edge%20AI-red)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

---

## 📌 Project Overview
The pharmaceutical industry requires **high precision** in medicine packaging to ensure **patient safety**, **regulatory compliance**, and **product integrity**. Manual inspection methods are **slow**, **inconsistent**, and **error-prone**, making automation essential.

This project introduces an **AI-powered quality inspection system** that:
- Uses **YOLOv5** for real-time defect detection.
- Controls a **3-DOF SCARA Robot** for pick-and-place operations.
- Runs on **Raspberry Pi 4** for **edge computing**.

### ✅ Key Highlights:
✔ Real-time detection of defective and non-defective medicine boxes  
✔ Fully automated inspection system with robotic handling  
✔ Accuracy of **95% on custom dataset**  
✔ Lightweight deployment using Raspberry Pi for industrial environments  

---

## 🎯 Objectives
- Automate quality inspection in pharmaceutical packaging.
- Detect defects such as **improper sealing, damaged packaging, and incorrect labeling**.
- Reduce **manual errors** and **increase inspection speed**.
- Achieve **real-time defect detection** and reporting.

---

## 🛠 Technologies Used
| **Category**         | **Tools & Technologies**                          |
|----------------------|---------------------------------------------------|
| **Programming**     | Python, OpenCV, PyTorch                           |
| **Deep Learning**   | YOLOv5, ResNet, GoogleNet, MobileNetV2           |
| **Hardware**        | Raspberry Pi 4, Camera Module, NEMA17 Stepper Motors |
| **Robotics**        | SCARA Robot (3 DOF)                              |
| **Design**          | SolidWorks                                       |
| **Simulation**      | MATLAB                                           |

---

## 🎥 Demo
![Live Demo GIF](images/demo.gif)  
*Watch the [Full Video Demo](https://youtube.com/your-demo-link) for real-time performance.*

---

## 📐 System Architecture
![System Architecture](images/architecture.png)

**Workflow:**
1. Camera captures high-resolution images of medicine boxes.
2. **YOLOv5 model** detects defects (sealed/unsealed, damaged packaging).
3. SCARA Robot performs **pick-and-place** operations:
   - Non-defective → Production line
   - Defective → Rejection bin
4. Results displayed on **GUI** for operator monitoring.

---

## 🔍 Features
✔ **Real-time defect detection** using YOLOv5  
✔ **Automated pick-and-place** with SCARA Robot  
✔ **Edge AI deployment** on Raspberry Pi  
✔ **GUI for easy monitoring and manual override**  
✔ **Accuracy > 95%** on custom dataset  

---

## 📂 Repository Structure
