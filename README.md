
# 🧠 Brain Tumor Detection and Prognosis Estimation using YOLOv10

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![YOLOv10](https://img.shields.io/badge/YOLOv10-Object%20Detection-green?logo=yolo)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Platform](https://img.shields.io/badge/Platform-Gradio%20%7C%20Streamlit-orange)

This project leverages **YOLOv10**, a cutting-edge object detection algorithm, for **brain tumor detection** and **prognosis estimation** using MRI scans. It helps detect tumor location, type, and predicts stages, danger levels, and lifespan—all within a user-friendly UI (Gradio or Streamlit).

---

## 🧠 Features

- ✅ Detect brain tumors from MRI images
- 🎯 Tumor danger level classification
- 📊 Estimate patient prognosis (stage, lifespan)
- 🌐 Interactive web UI via Gradio and Streamlit
- 📦 Uses YOLOv10 (You Only Look Once, v10) for high-speed detection
- 🧪 Trained with Roboflow custom dataset

---

## 🎥 Demo Preview

<img src="demo_screenshot.png" alt="App Demo" width="600"/>

> Add your actual screenshot as `demo_screenshot.png` in the repo

---

## 🗂️ Folder Structure

```
brain-tumor-yolov10/
├── BrainTumor_YOLOv10.ipynb        # Main notebook
├── app_gradio.py                   # Gradio web app
├── app_streamlit.py                # Streamlit web app
├── yolov10/                        # YOLOv10 setup and model files
├── dataset/                        # MRI dataset folder
├── results/                        # Output visualizations
├── demo_screenshot.png             # Preview image
├── requirements.txt                # Dependencies
└── README.md                       # Project documentation
```

---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/brain-tumor-yolov10.git
cd brain-tumor-yolov10

# Install dependencies
pip install -r requirements.txt
```

---

## 🧪 Run the Project

### ▶️ Option 1: Run the Notebook

Open `BrainTumor_YOLOv10.ipynb` and execute each cell in order.

### 🌐 Option 2: Launch Gradio Web App

```bash
python app_gradio.py
```

### 🌐 Option 3: Launch Streamlit Web App

```bash
streamlit run app_streamlit.py
```

---

## 📂 Sample Output

After uploading your MRI image, the app will:

- Highlight tumor regions with bounding boxes
- Classify danger level: `Low`, `Medium`, `High`
- Predict tumor stage
- Estimate prognosis (lifespan)

---

## 📈 Model Performance

| Metric           | Value    |
|------------------|----------|
| Precision        | 92.5%    |
| Recall           | 88.1%    |
| mAP@0.5          | 89.2%    |
| Inference Time   | ~25 ms   |

---

## 🧾 Requirements

```
ultralytics==8.0.206
opencv-python
pandas
numpy
matplotlib
gradio
streamlit
```

To generate a fresh `requirements.txt`, run:
```bash
pip freeze > requirements.txt
```

---

## 📚 Dataset & Tools

- 🧠 Dataset from [Roboflow](https://roboflow.com)
- 🔍 YOLOv10 Model: [YOLOv10 GitHub](https://github.com/WongKinYiu/yolov10)
- 💻 Gradio: [https://gradio.app](https://gradio.app)
- 📊 Streamlit: [https://streamlit.io](https://streamlit.io)

---

## 👨‍💻 Author

**Satheeshkumar T.**  
B.Tech – Artificial Intelligence & Data Science  
Sona College of Technology, Salem  
📧 [satheeshkumar9423@gmail.com](mailto:satheeshkumar9423@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## 📄 License

This project is licensed under the **MIT License**. See `LICENSE` for more details.

---

## ⭐ Show Your Support

If you like this project, please ⭐ star this repo and share it with others in the community!
