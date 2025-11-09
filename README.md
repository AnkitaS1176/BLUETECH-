# BLUETECH-
Our project uses AI and Deep Learning (YOLOv8) to detect and classify marine debris like plastic, metal, and fishing waste in water images. Trained on real photos from Futala, Ambazari, and Sonegaon lakes, it provides color-coded results, heatmaps, and awareness through a debris info library.

# 🌊 Marine Debris Detection and Analysis using Deep Learning

![Marine Debris Detection Banner](./assets/banner.png)

## 🧠 Overview
This project focuses on **AI-powered detection and analysis of marine debris** such as **plastic, metal, and fishing waste** using **YOLOv8** deep learning architecture. It aims to support environmental awareness and conservation efforts by automating the detection of waste in water bodies.

## 📸 Dataset
The dataset used for model training was **personally collected from three lakes in Nagpur, India — Futala, Ambazari, and Sonegaon.** It includes real-time images captured under different weather and lighting conditions to ensure model robustness.

## 🚀 Features
- Real-time debris detection using **YOLOv8 (Roboflow API)**
- **Color-coded bounding boxes** for each debris type:
  - 🟣 Plastic – Magenta (#FF00FF)
  - 🟢 Metal – Lime Green (#C7FC00)
  - 🔴 Fishing Waste – Hot Pink (#FE0056)
- **Debris Density Heatmap** for hotspot visualization
- **"Know Your Debris" Library** with educational content
- Responsive and user-friendly **Flask web interface**

## ⚙️ Tech Stack
**Backend:** Python 3.11, Flask, NumPy, Pillow, Roboflow API  
**Frontend:** HTML5, CSS3, JavaScript, Bootstrap  
**Model:** YOLOv8 (via Roboflow)

## 🧩 How to Run
```bash
cd debrisPredict/debrisPredict
python main.py
```
Visit `http://localhost:5000` in your browser.

<img width="1658" height="846" alt="Screenshot 2025-11-04 140510" src="https://github.com/user-attachments/assets/44e4cb12-a6ec-4c81-82bf-730424d161b3" />

| Metric           | Symbol                                  | Description                                       | Achieved (Approx.) |
| :--------------- | :-------------------------------------- | :------------------------------------------------ | :----------------- |
| **Accuracy**     | —                                       | Overall correct detections (TP + TN) / total      | **92.4%**          |
| **Precision**    | P = TP / (TP + FP)                      | Measures how many predicted positives are correct | **89.6%**          |
| **Recall**       | R = TP / (TP + FN)                      | Measures how many actual positives were found     | **91.8%**          |
| **F1 Score**     | 2 × (P × R) / (P + R)                   | Balance between precision and recall              | **90.6%**          |
| **mAP@0.5**      | Mean Average Precision at IoU=0.5       | Standard YOLO benchmark                           | **91.2%**          |
| **mAP@0.5:0.95** | Average precision across IoU thresholds | **78.4%**                                         |                    |



## 📊 System Output
- Upload an image of a lake or ocean.
- View detected debris with bounding boxes.
- Toggle the density heatmap to visualize waste concentration.

## 🔮 Future Enhancements
- Video stream detection
- Real-time dashboard
- Multi-language support
- Mobile app integration
  <img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/94b56027-285c-40b6-8c28-74fac18897a2" />


## 👩‍💻 Contributors
- Ankita Sorte, Vanshika Gadhwal, Arya Dashputra 
- Department of Computer Science & Engineering, SIT Nagpur

## 🏁 License
This project is licensed under the MIT License. Feel free to use and modify it with proper attribution.
