# 🚗 Driver Drowsiness Detection System (DDDS)

A real-time computer vision project to detect driver drowsiness and yawning using facial landmark detection, helping to reduce road accidents caused by fatigue.

---

## 🎯 **Objective**

To build a real-time system that monitors a driver’s eye closure and yawning patterns using a webcam and alerts them instantly with an alarm when drowsiness or frequent yawning is detected.

---

## 📌 **Use Case**

- Long-distance truck, taxi, or bus drivers
- Fleet management systems to enhance driver safety
- Integration into car dashboards or mobile safety apps
- Personal use for late-night drivers or road trips

---

## 🛠 **Tech Stack**

- Python
- OpenCV (real-time image processing)
- Dlib (facial landmark detection)
- Scipy (distance calculations)
- Imutils (image utility functions)
- Pygame (to play alarm sound)
- Pre-trained model: `shape_predictor_68_face_landmarks.dat`

---


## ⚙️ **How It Works**

1. Captures live video from the webcam.
2. Uses Dlib to detect 68 facial landmark points.
3. Calculates:
   - **EAR (Eye Aspect Ratio):** Detects prolonged eye closure.
   - **MAR (Mouth Aspect Ratio):** Detects yawning.
4. If EAR remains below 0.25 for 25 consecutive frames → plays alarm.
5. If MAR exceeds 0.75 → counts it as a yawn.
6. Displays EAR, MAR, and yawn count on the video frame.

---

## ✨ **Features**

✅ Real-time video processing  
✅ Detects eye closure and yawning  
✅ Audible alarm if driver becomes drowsy  
✅ Live stats display on the video frame  
✅ Simple, explainable, and lightweight  


---

## ⭐ **Contributing**

Contributions, pull requests, and suggestions are welcome!  
Feel free to fork this repository and improve the project.

---

## ✅ **Contact**

For any queries, suggestions, or collaboration:

- GitHub: [Raghu-2005]
- Email: [lraghuram14@gmail.com]

---


