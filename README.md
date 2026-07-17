#  LifeSaver-AI

An AI-powered **Vehicle Accident Detection System** developed using **Python, TensorFlow, Keras, and OpenCV**. The project leverages Deep Learning and Computer Vision techniques to classify road images into **Accident** and **Non-Accident** categories, providing an automated approach for accident detection.

---

##  Overview

LifeSaver-AI demonstrates a complete deep learning workflow for image classification, including:

- Data preprocessing
- CNN model development
- Model training and validation
- Accident prediction on unseen images
- Performance visualization

The project is implemented using Jupyter Notebooks, making each stage of the pipeline easy to understand and reproduce.

---

##  Features

-  Binary image classification (Accident / Non-Accident)
-  Convolutional Neural Network (CNN) for image classification
-  Image preprocessing using OpenCV
-  Model training, validation, and testing
-  Training and validation performance visualization
-  Prediction on unseen images
-  Organized project structure for reproducibility

---

##  Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | OpenCV |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |

---

##  Project Workflow

### 1. Data Preprocessing
- Load and organize the dataset
- Resize and preprocess images
- Prepare training, validation, and testing datasets

### 2. Model Training
- Build a Convolutional Neural Network (CNN)
- Train the model using TensorFlow/Keras
- Monitor training and validation performance

### 3. Accident Prediction
- Load the trained model
- Predict Accident and Non-Accident images
- Visualize prediction results

---

##  Results

The project successfully demonstrates:

- Binary classification of road images into **Accident** and **Non-Accident**
- CNN model training and evaluation
- Prediction on unseen images
- Training, validation, and testing outputs
- Performance visualization through accuracy and loss curves

Prediction outputs and model visualizations are available in the project notebooks and the **proofImages** directory.

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/DuaSaba/LifeSaver-AI
cd LifeSaver-AI
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

Launch Jupyter Notebook and execute the notebooks in the following order:

1. `01_DataPreprocessing.ipynb`
2. `02_ModelTraining.ipynb`
3. `03_AccidentPrediction.ipynb`

---

##  Future Improvements

- Deploy the model using Flask or FastAPI
- Real-time accident detection from live video streams
- Improve accuracy using larger datasets and transfer learning
- Integrate object detection models such as YOLO
- Develop a mobile or web application for real-time monitoring

---

