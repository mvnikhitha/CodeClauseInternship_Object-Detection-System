# 🖼️ Object Detection System (TASK 2)🕵️‍♂️

This project focuses on creating an **Object Detection System** capable of detecting and classifying objects in images or video streams. It leverages pre-trained models such as **YOLO (You Only Look Once)** or **Faster R-CNN** and customizes them to detect specific objects of interest. This system utilizes real-time image processing and can be used for various applications like surveillance, autonomous vehicles, and image analysis.

Created as part of the **CodeClause Internship**.

---

## 📌 Features

- Real-time object detection in images and video streams
- Detects multiple objects within a single frame
- Customizable to detect specific objects
- Utilizes pre-trained models like YOLO or Faster R-CNN
- Easy-to-use interface with OpenCV for video stream processing

---

## 🧠 How the Object Detection Works

The system uses advanced deep learning techniques and pre-trained object detection models. The primary models used are:

- **YOLO (You Only Look Once)**: A fast and efficient model for object detection that can detect multiple objects in real-time.
- **Faster R-CNN**: A more accurate but computationally intensive model, ideal for high-accuracy object detection.

The models are trained to detect and classify objects by processing images or video streams, providing bounding boxes and labels for each detected object.

---

## ▶️ How to Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
```
### Step 2: Install Dependencies
Make sure you have all the required dependencies installed
```bash
pip install -r requirements.txt
```
### Step 3: Open the Jupyter Notebook or Python Script
You can open the notebook or Python script to run the object detection system.
```bash
object_detection.ipynb
```
### Step 4: Run the Detection
 - If using a video stream, the script will start processing the video feed from your webcam.
 - If using static images, you can provide a path to an image file for detection.
 - The system will display bounding boxes around detected objects and classify them with labels.
   
## 💻 Technologies Used

- Python
- TensorFlow/Pytorch 
- OpenCV
- YOLO/Faster R-CNN

## Author 
M V Nikhitha

## 👩‍🎓 Acknowledgement
 - This project was built as part of the CodeClause Internship.
