# Weapon-Detection-for-Police-use
AI-powered weapon detection system built for a project. Uses COCO-SSD and computer vision to detect guns/knives in CCTV or drone feeds, sending instant alerts to law enforcement for faster response and improved public safety.
# 🔍 Weapon Detection System – Police Hackathon Project  

This project was developed during a **Police Hackathon** to enhance public safety using **AI-powered weapon detection**. The system leverages the **COCO-SSD deep learning model** to detect weapons (such as guns and knives) in real-time from **CCTV or drone feeds**, instantly sending alerts to law enforcement for faster response.  

---

## Key Features  
- **Real-time Detection** – Identifies weapons in live video streams or uploaded images.  
- **AI-Powered Vision** – Built on the **COCO-SSD model** for reliable detection.  
- **Instant Alerts** – Generates alerts when a weapon is detected.  
- **Scalable** – Works with CCTV cameras, drones, or cloud deployments.  
- **Lightweight** – Optimized for edge and resource-limited devices.  

---

## Tech Stack  
- **Programming Language:** Python  
- **Libraries:** OpenCV, TensorFlow  
- **Model:** COCO-SSD (pre-trained on COCO dataset)  
- **Backend (Optional):** Flask / FastAPI for integration with other systems  
- **Hardware:** Surveillance cameras, drone feeds, or local webcams  

---

## Use Cases  
- Monitoring crowded or high-security areas (airports, stations, events).  
- Assisting police with **real-time situational awareness**.  
- Reducing response time to potential threats.  
- Supporting **crime prevention and investigation**.  

---

## Future Enhancements  
- Integration with **facial recognition** for suspect identification.  
- **GPS-enabled drones** for live monitoring and tracking.  
- Automated **report generation** and database integration.  
- Improving accuracy for **concealed weapon detection**.  

---

##  How to Run  
1. Clone this repository:  
   ```bash
2. Install required dependencies:
    pip install -r requirements.txt

3. Run the detection script:
     python detect.py

4.Provide a camera feed / video file / image as input.
5. The system will display detections and generate alerts if a weapon is found.
