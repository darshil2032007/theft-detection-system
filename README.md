# 🛒 Theft Detection System

An AI-powered computer vision application built with **Streamlit**, **OpenCV**, and a **custom-trained YOLO model** to analyze retail surveillance videos.
The system detects **cash drawer state (OPEN / CLOSED)** and **theft events**, while automatically capturing evidence frames.

---

## 🚀 Project Overview

This application performs intelligent video analysis to:

✔ Detect cash drawer activity
✔ Recognize drawer OPEN / CLOSED state
✔ Identify theft events
✔ Display real-time inference results
✔ Automatically save evidence frames

This project is designed for **retail security**, **loss prevention research**, and **AI/ML demonstration**.

---

## 🎯 Key Features

* 🧠 Custom YOLO object detection model
* 🗄 Drawer state detection (Open / Closed)
* 🚨 Theft event detection
* 📸 Automatic evidence frame capture
* 🎥 Video upload & processing
* 🌐 Interactive Streamlit web interface

---

## 🏗 Tech Stack

* **Python**
* **Streamlit**
* **OpenCV (Headless)**
* **Ultralytics YOLO**
* **NumPy**
* **Pandas**
* **PyTorch**

---

## 📂 Project Structure

```
TheftDetectionSystem/
│── app.py
│── requirements.txt
│── runtime.txt
│── models/
│     └── best2.pt
│── evidence/   (generated at runtime)
```

---

## ⚙️ Local Installation

Clone the repository:

```bash
git clone https://github.com/darshil2032007/theft-detection-system.git
cd theft-detection-system
```

Create a virtual environment (recommended):

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

---

## ▶️ Usage

- 1️⃣ Launch the app
- 2️⃣ Upload a surveillance / retail video
- 3️⃣ Click **Start Detection**
- 4️⃣ View drawer & theft detection results
- 5️⃣ Evidence frames saved automatically

---

## 🧠 Model Details

* Framework: **Ultralytics YOLO**
* Custom-trained for:

  * Drawer detection
  * Theft detection

Model location:

```
models/best2.pt
```

---

## 📸 Evidence Capture

When theft is detected:

✔ Frame saved automatically
✔ Cooldown prevents duplicate saves
✔ Stored in `/evidence` folder

---

## 🌐 Deployment

This application is deployable via:

✔ Streamlit Community Cloud
✔ Render
✔ Railway
✔ VPS / Cloud VM

---

## ⚠️ Important Notes

* Uses `opencv-python-headless` for cloud compatibility
* Evidence folder is runtime-generated
* Streamlit Cloud storage is temporary (ephemeral)


## 👨‍💻 Author

**Darshil Savaliya**

---

## 📜 License

This project is intended for academic / demonstration purposes.
