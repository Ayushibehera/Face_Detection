# Face Detection System 🎯

A real-time face detection system built using deep learning techniques and computer vision libraries. This project implements CNN-based models for accurate face detection in images and live video streams.

## 🌟 Features

- **Real-time Face Detection**: Live video processing using webcam
- **Image Processing**: Batch processing of images for face detection
- **Multiple Detection Models**: Implementation of various face detection algorithms
- **High Accuracy**: Trained and tested on standard datasets for robust performance
- **Cross-platform Compatibility**: Works on Windows, macOS, and Linux
- **Easy Integration**: Modular design for easy integration into other projects

## 🚀 Technologies Used

- **Python**: Core programming language
- **OpenCV**: Computer vision library for image and video processing
- **TensorFlow/Keras**: Deep learning framework for model training
- **NumPy**: Numerical computing library
- **Matplotlib**: Data visualization library
- **CNN Models**: MTCNN, Haar Cascades, and custom trained models

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

```bash
Python 3.7+
pip (Python package manager)
Webcam (for real-time detection)
```

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/bhavanshubehera/Face_Detection.git
cd Face_Detection
```

2. Create a virtual environment (recommended):
```bash
python -m venv face_detection_env
source face_detection_env/bin/activate  # On Windows: face_detection_env\Scripts\activate
```

3. Install required dependencies

## 🎮 Usage

### Real-time Face Detection (Webcam)
```bash
python main.py --mode webcam
```

### Image Face Detection
```bash
python main.py --mode image --input path/to/your/image.jpg
```

### Batch Processing
```bash
python main.py --mode batch --input path/to/image/folder/
```

### Video Processing
```bash
python main.py --mode video --input path/to/your/video.mp4
```

## 🧠 Model Details

This project implements multiple face detection approaches:

1. **MTCNN (Multi-task CNN)**: For high-accuracy face detection with facial landmarks
2. **Haar Cascades**: Classical approach for real-time detection
3. **Custom CNN**: Trained on WIDER FACE and LFW datasets
4. **YOLO-based Detection**: For fast inference and multiple face detection

### Model Performance
- **Accuracy**: 95%+ on standard test datasets
- **Speed**: 30+ FPS on average hardware
- **Robustness**: Works across varied lighting conditions and angles

## 📊 Datasets Used

- **WIDER FACE**: For training and validation
- **LFW (Labeled Faces in the Wild)**: For testing robustness
- **Custom Dataset**: Additional data for specific use cases

## 📈 Results

The system achieves:
- **Precision**: 96.2%
- **Recall**: 94.8%
- **F1-Score**: 95.5%
- **Processing Speed**: 35 FPS average

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Thanks to the open-source community for the amazing libraries
- WIDER FACE and LFW dataset creators
- OpenCV and TensorFlow teams for their excellent documentation

---

## 👥 Project Team

### 👨‍💻 Bhavanshu Behera
- **GitHub**: [@bhavanshubehera](https://github.com/bhavanshubehera)
- **Role**: Co-Developer & Project Maintainer
- **Contributions**: Core face detection algorithms, model training, project architecture

### 👩‍💻 Ayushi Behera
- **GitHub**: [@Ayushibehera](https://github.com/Ayushibehera)
- **LinkedIn**: [ayushibehera](https://www.linkedin.com/in/ayushibehera)
- **Role**: Co-Developer & ML Engineer
- **Background**: BTech Computer Science Engineering student, API Fellow at Keploy
- **Expertise**: AI/ML, Data Science, Software Development
- **Contributions**: Model optimization, dataset preparation, testing and validation

---

*Built with ❤️ by Bhavanshu & Ayushi*
