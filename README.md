# 🌿 Leaf Disease Detection App

The Leaf Disease Detection App is a machine learning-based application designed to help farmers, gardeners, and agricultural professionals identify plant diseases from leaf images. The app uses a deep learning model to classify diseases and provides detailed information about the disease, its severity, causes, and prevention methods. It also supports real-time camera capture and video stream analysis.

##  Disease Classification

**Detects and classifies plant leaf diseases into 7 categories:**

<div align="center">

| Category | Icon | Description |
|----------|------|-------------|
| **Bacteria** | 🦠 | Bacterial leaf spots |
| **Fungi** | � | Fungal infections |
| **Healthy** | ✅ | Normal leaves |
| **Nematode** | 🪱 | Nematode damage |
| **Pest** | 🐛 | Insect infestation |
| **Phytopthora** | 🌧️ | Water mold disease |
| **Virus** | ☣️ | Viral infections |

</div>
- 🎯 95% classification accuracy

- 🖼️ Processes leaf images in <1s
  
- 📱 Mobile-friendly interface
  
- 📊 Detailed health reports

## 🚀 Core Features  
- **📸 Real-Time Camera**  
  _Capture leaf images for instant analysis_  
- **🚁 Video Analysis**  
  _Supports drone streams for large-scale monitoring_  
- **🔊 Voice Guidance**  
  _Audio explanations of results_  
- **✨ Gradio UI**  
  _No-code interface for easy adoption_  

## 🚀 Powered By  
[![TF](https://img.shields.io/badge/DenseNet121-TensorFlow-FF6F00)](https://www.tensorflow.org/)  
[![OpenCV](https://img.shields.io/badge/RealTime-OpenCV-5C3EE8)](https://opencv.org/)  
[![gTTS](https://img.shields.io/badge/Audio-gTTS-34A853)](https://gtts.readthedocs.io/)  
[![Gradio](https://img.shields.io/badge/UI-Gradio-FF4B4B)](https://gradio.app/)  
[![Pandas](https://img.shields.io/badge/Data-Pandas-150458)](https://pandas.pydata.org/)  

### 📲 Usage Guide
# Upload Image:
Go to the Upload Image tab.
Upload a leaf image and click Submit.
The app will display the disease name, severity, cause, and prevention tips.

✨ Output:
![Image](https://github.com/user-attachments/assets/bce19b59-1b3b-44b2-85e4-e5a5a67b19db)
### Real-Time Camera:

📸 How to use:
Go to the Real-Time Camera tab.
Click Capture Image to take a photo using your device's camera.
The app will analyze the image and provide results.

⚡ Live Results:
![Image](https://github.com/user-attachments/assets/a3b7e143-6803-43c9-813d-fbac1b911d73)
### Video Stream Analysis:
Go to the Video Stream Analysis tab.
Upload a video file or provide a stream URL.
Click Analyze Video to process the video and detect diseases.
🌐 Best for:

Drone footage

Greenhouse monitoring

Batch processing

### Chatbot:
Go to the Chatbot tab.
Ask questions about plant diseases (e.g., "What causes fungal infections?").
The chatbot will provide detailed responses with audio feedback.

## 🌿 Dataset

**3,076 curated plant leaf images** across 7 disease categories:

<div align="center">

| Class        | Samples | Example | Description |
|--------------|---------|---------|-------------|
| **Bacteria** | 450     | 🦠      | Bacterial leaf spots |
| **Fungi**    | 489     | 🍄      | Fungal infections |
| **Healthy**  | 520     | ✅      | Disease-free leaves |
| **Nematode** | 412     | 🪱      | Nematode damage |
| **Pest**     | 398     | 🐛      | Insect infestations |
| **Phytopthora**| 407    | 🌧️      | Water mold disease |
| **Virus**    | 400     | ☣️      | Viral infections |

</div>

Dataset_link=https://www.kaggle.com/datasets/nirmalsankalana/potato-leaf-disease-dataset

Model Performance
Test Accuracy: 95.17%
Loss: 0.1659

## 🚧 Future Improvements

### 🌱 Expanded Coverage
| Goal                     | Status  | Icon |
|--------------------------|---------|------|
| Add 50+ plant species    | Planned | 🌿   |
| Support rare diseases    | Roadmap | 🦠   |
| Tree/bark pathology      | Research| 🌳   |

🖥️ Enhanced Features
Real-time drone analytics 🚁
(Field-scale disease mapping)

Multi-language TTS 🔊
(Spanish, Hindi, Mandarin support)

Soil health correlation 🌱
(Disease prediction models)
### Acknowledgments
TensorFlow and Keras for providing the deep learning framework.
Gradio for the user-friendly interface.
OpenCV for real-time image and video processing.
gTTS for text-to-speech functionality.
![Image](https://github.com/user-attachments/assets/6bb1028c-2b80-44de-8e62-0c7e67c800e1)

## 👥 Contributing

```bash
# 1. Fork & clone the repo
gh repo fork Ananya2312/smartslideconverter && cd smartslideconverter

# 2. Create a feature branch
git checkout -b feat/your-feature

# 3. Commit changes
git commit -m "feat: your contribution"

# 4. Push and open PR
git push origin feat/your-feature


