# Enhanced-Aim-and-Strategic-Planning-in-FPS-Games-
This repository contains the final implementation of my AI-driven aim analysis and strategy generation system for Valorant. It includes gameplay data processing, object detection using YOLOv8, reinforcement learning for tactical feedback, and performance evaluation tools.

# 🎯 AI-Powered Aim Analysis & Strategy Generation for Valorant

This project presents an AI-based system designed to enhance player performance in the first-person shooter game **Valorant**. It leverages **YOLOv8** for object detection and **reinforcement learning** for generating adaptive strategies, using real gameplay footage as input.

---

## 📌 Features

- 🔍 Object detection of enemies, teammates, crosshairs, and enemy heads using YOLOv8.
- 📊 Aim accuracy analysis with metrics like crosshair distance and headshot ratio.
- ♟️ Reinforcement Learning agent for aim adjustment and strategy suggestions.
- 🔥 Heatmaps and performance plots for visualizing player behavior.
- 📁 Compatible with custom-labeled gameplay datasets.

---

## 📂 Dataset Links

- 🗂 **Object Detection Dataset**  
  - [Kaggle](https://www.kaggle.com/datasets/Dasun01/valorant-object-detection-dataset)  
  - [Hugging Face](https://huggingface.co/datasets/Dasun01/Valorant-Object-Detection-Dataset)

- 📋 **Tactical Strategy Dataset**  
  - [Kaggle](https://www.kaggle.com/datasets/Dasun01/valorant-strategies)  
  - [Hugging Face](https://huggingface.co/datasets/Dasun01/valorant_strategies)

---

## 🧠 Technologies Used

- YOLOv8 (Ultralytics)
- Python
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn
- Q-Learning (Reinforcement Learning)
- Roboflow (Annotation)
- Google Colab Pro (Model training)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/valorant-aim-analysis.git
   cd valorant-aim-analysis
