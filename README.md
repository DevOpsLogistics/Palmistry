# Palmistry CNN - AI Fortune Teller 

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-15.0-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.111-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.10-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![CNN](https://img.shields.io/badge/Deep_Learning-CNN-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

</div>

##  Introduction
Welcome to the **Palmistry CNN** project! This repository contains an advanced Convolutional Neural Network (CNN) multi-output model built to analyze palm lines and predict 8 aspects of a person's life:
- **General Fortune**
- **Love & Marriage**
- **Career & Work**
- **Health**
- **Finance & Wealth**
- **Future Prospects**
- **Past Life**
- **Next Life**

##  Features
- **Multi-Output CNN Architecture**: Predicts multiple life aspects simultaneously using a shared feature extractor.
- **Data Augmentation**: Robust training with random flips, rotations, and zooms.
- **Interactive UI**: Built-in Jupyter widget (or web interface) for seamless image upload and real-time prediction.
- **Detailed Life Analysis**: Generates comprehensive Vietnamese readings based on palm traits.

##  Tech Stack
Based on the project's ecosystem architecture:
- **AI & Computer Vision**: TensorFlow/Keras, OpenCV, Python 3.11
- **Backend API**: FastAPI 0.111
- **Web Frontend**: Next.js 15.0, React 19.0, TypeScript 5.0

##  Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/DevOpsLogistics/Palmistry.git
   cd Palmistry
   ```
2. Install the required Python dependencies:
   ```bash
   pip install tensorflow opencv-python pandas matplotlib seaborn ipywidgets
   ```
3. Open `Palmistry.ipynb` in VS Code or Jupyter Notebook.

##  Usage
1. Run all cells in `Palmistry.ipynb`.
2. Scroll to the bottom and click the **"Tải ảnh lên"** (Upload Image) button.
3. Select a clear image of your palm (`.jpg`, `.png`).
4. Read your detailed fortune and view the destiny radar chart!

##  Disclaimer
This project is for educational and entertainment purposes. AI fortune telling should not replace professional medical, financial, or psychological advice.
