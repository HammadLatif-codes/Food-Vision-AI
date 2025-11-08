# 🍔 Food Vision AI – Capstone Project (TensorFlow)

**Food-101 Image Classification** using **EfficientNetB7** and **TensorFlow**.  
This project was developed as my Deep Learning Capstone for the BS Computer Science program.

---

## 🧠 Overview
The model classifies food images into 101 categories from the **Food-101 dataset**.  
It applies **transfer learning** on **EfficientNetB7** and achieves ~**67.76% accuracy** on the test set.

---

## 📁 Files in This Repository
| File | Description |
|------|--------------|
| Food_Vision_Capstone_Project.ipynb | Jupyter/Colab notebook with training and evaluation code |
| Final Report (Capstone Project).pdf | Full written report |
| Food Vision AI Capstone Project.pptx | Presentation slides |
| equirements.txt | Python dependencies |
| .gitignore | Ignore rules for repo cleanliness |

---

## 🧰 Setup (Run Locally or on Colab)
`ash
pip install -r requirements.txt
import tensorflow_datasets as tfds
tfds.load("food101", as_supervised=True)

🚀 Future Improvements

Export and host trained model for inference

Add Streamlit web demo

Fine-tune on additional data for higher accuracy© 2025 Hammad Latif
