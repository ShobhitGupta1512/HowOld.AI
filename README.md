# 👤 Age and Gender Prediction App  

A Streamlit-based web app that predicts **age** and **gender** from an uploaded photo or a live camera feed.  
The app uses a **Keras deep learning model** for predictions and **OpenCV Haar Cascade** for face detection.  


---

## 📌 Live Demo  
👉 [Try it here](https://howold.streamlit.app)  

---
<img width="1347" height="679" alt="image" src="https://github.com/user-attachments/assets/e013af77-c819-490d-a6b8-fc64cf177493" />
This is the user interface of the **Age and Gender Prediction App** after loading the model successfully.


## ✨ Features  
✔️ Upload an image or use live camera input  
✔️ Automatic **face detection & cropping** using OpenCV  
✔️ Preprocessing pipeline (grayscale, normalization, resizing)  
✔️ Predicts **gender** (Male/Female) and **approximate age**  
✔️ Clean and responsive Streamlit interface  
✔️ Sidebar with instructions and notes  

---

## 📂 Project Structure  

```bash
project-folder/
├── model.keras           # Pre-trained Keras model
├── app.py                # Streamlit app (main file)
├── requirements.txt      # Dependencies
└── README.md             # Project documentation


