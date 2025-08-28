# 🚁 Smart Drone Surveillance System 🔍

**Smart Drone Surveillance System** is an AI-powered computer vision project designed to detect survivors in drone footage for emergency rescue operations. The system combines **YOLOv8 object detection** with motion analysis and generates **heatmaps** to highlight areas where survivors are likely present, aiding rescue teams in disaster management scenarios.

---

## ✨ Features

- Detects humans (survivors) in drone footage using **YOLOv8**
- Motion-based filtering using **Optical Flow** to reduce false positives
- Tracks survivor locations across frames
- Generates **Gaussian and Turbo heatmaps** to visualize high-activity areas
- Saves annotated output videos for review

---

## 📂 Project Structure

```
  smart-drone-surveillance/
  │── notebooks/
  │   └── Smart_Drone_Surveillance.ipynb    
  │── src/
  │   └── detection.py                      
  │── sample_videos/
  │   └── drone_video1.mp4                  
  │── outputs/
  │   ├── output_video.mp4                  
  │   ├── turbo_heatmap_output.mp4          
  │   └── gaussian_heatmap.png             
  │── requirements.txt                 
  │── README.md
```
---

## 🚀 Installation & Usage

1. **Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/smart-drone-surveillance.git
cd smart-drone-surveillance
```
2. **Install dependencies**
```bash
pip install -r requirements.txt
```
3. **Run the notebook**
- Open notebooks/Smart_Drone_Surveillance.ipynb in Google Colab.
- Upload your input video (drone_video1.mp4) if not already included.
- Run all cells to generate output videos and heatmaps.

---

## 📊 Sample Output

- Detection Video: output_video.mp4
- Turbo Heatmap Video: turbo_heatmap_output.mp4
- Gaussian Heatmap Image: gaussian_heatmap.png

---

## 🛠️ Tech Stack

- Python 3.x
- OpenCV – Video processing & computer vision
- YOLOv8 (Ultralytics) – Object detection
- Seaborn & Matplotlib – Heatmap visualization
- SciPy – Gaussian filtering for heatmaps

---

## 📌 Future Improvements

- Train YOLO on a custom drone dataset for higher detection accuracy
- Add GPS mapping of detected survivors for rescue coordination

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to suggest improvements or add new features, feel free to fork the repo and open a PR.
Please ensure your contributions follow our code style and commit guidelines.

---
