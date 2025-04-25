# Facial-recognition-system


This project is a real-time facial recognition system that leverages **Convolutional Neural Networks (CNN)**, **Local Binary Patterns (LBP)**, and **Haar Cascade** classifiers for accurate face detection and recognition. It is further enhanced with an **automated email alert system** that captures and sends a photo of any **unauthorized person** who appears in front of the camera.

---

### 🔍 Features
- **Real-time Face Detection** using Haar Cascade classifiers.
- **LBP Feature Extraction** for texture-based face encoding.
- **CNN-based Classification** of known faces with high accuracy.
- **Email Alert System**: Sends an automated email with the intruder's photo if an unauthorized face is detected.
- User-friendly and modular design for training, recognition, and alerting.

---

### 🧠 Techniques Used
- **Haar Cascade** for facial region detection.
- **Local Binary Patterns (LBP)** for extracting key facial features.
- **Convolutional Neural Networks (CNN)** for classifying known and unknown faces.
- **SMTP (Simple Mail Transfer Protocol)** for sending real-time alert emails with image attachments.

---

### 🛠️ Technologies
- Python  
- OpenCV  
- NumPy, Pandas  
- Keras (CNN)  
- Scikit-learn  
- smtplib 
- Matplotlib / Seaborn  

---

### 🚀 How It Works
1. **Face Detection** is done using Haar Cascade.
2. **LBP** extracts texture features from the face.
3. **CNN** classifies the face as known or unknown.
4. If **unauthorized**, the system:
   - Captures the intruder’s image
   - Sends an **alert email** with the image to the registered recipient

---

### 📧 Email Alert Sample
> Subject: ⚠️ Alert: Unauthorized Person Detected  
> Body: “An unknown individual has been detected. See attached image.”  
> Attachment: Captured intruder photo.

---

### 📌 Use Cases
- Smart Home Security  
- Office Attendance & Access Control  
- Surveillance Systems  
- School/College Entry Monitoring  
