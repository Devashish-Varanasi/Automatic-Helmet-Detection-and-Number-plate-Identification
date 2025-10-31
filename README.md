# Automatic-Helmet-Detection-and-Number-plate-Identification

## 🚀 Project Overview
Traffic accidents due to helmet non-compliance are a growing concern, making manual monitoring inefficient. This project presents an **automated helmet detection and number plate recognition system** using **deep learning and computer vision**. By integrating **YOLO-based object detection, image enhancement, and Optical Character Recognition (OCR)**, this system enhances road safety, reduces enforcement workload, and ensures compliance with helmet laws.

## 🏗️ Features
- **Real-time Detection**: Identifies motorcycles, helmets, and number plates from video input.
- **YOLO-based Deep Learning Model**: Ensures high-accuracy object detection.
- **OCR for Number Plate Recognition**: Extracts vehicle registration numbers.
- **Image Enhancement Techniques**: Improves number plate clarity for better OCR accuracy.
- **Automated Data Storage**: Saves violation records using **MongoDB/SQL**.
- **Scalable and Efficient**: Reduces manual effort and integrates with traffic management systems.

## 🔧 Tech Stack
- **Deep Learning**: YOLO (You Only Look Once) Object Detection
- **OCR**: OpenCV, Tesseract OCR
- **Image Processing**: Discrete Cosine Transform (DCT), Laplacian filter

## 📌 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/jaswanthkondeti/Automatic-Helmet-Detection-and-Number-plate-Identification.git
cd Automatic-Helmet-Detection-and-Number-plate-Identification
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Model for Object Detection
```bash
python app.py
```


## 🖼️ System Workflow
1. **Video Processing**: The system reads video frames and applies preprocessing.
2. **Object Detection**: YOLO detects motorcycles, helmets, and number plates.
3. **Violation Capture**: If a helmet is missing, the number plate is extracted.
4. **Image Enhancement**: Improves number plate visibility.
5. **OCR Processing**: Extracts text from the number plate.
6. **Data Storage**: Stores detected violations for further enforcement.

## 📊 Performance Metrics
| Model | Precision | Recall | F1-Score | Accuracy |
|--------|-----------|--------|----------|----------|
| Vehicle Detection | 90.7% | 93.0% | 91.8% | 84.9% |
| Helmet Detection | 90.4% | 93.5% | 91.9% | 84.8% |
| Number Plate Recognition | 93.2% | 97.0% | 95.1% | 89.0% |

## 🎯 Future Enhancements
- **Real-time Alert System**: Notify riders of violations instantly.
- **Night Vision Support**: Improve detection under low-light conditions.
- **Integration with Traffic Authority Databases**: Automate penalty issuance.

## 🤝 Contributing
Feel free to **fork**, submit issues, or make pull requests! Any contributions to improve this system are welcome.

---
🚀 **Let's make roads safer with AI-powered automation!**
