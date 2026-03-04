 Plant Disease Detection

Author: Hamza Asghar
GitHub: hamza5849

 Project Description

This project is a Plant Disease Detection system using Deep Learning (MobileNetV2) and the PlantVillage Dataset.
The model can classify plant leaves into three categories:

Healthy

Powdery Mildew

Other/Rest

The system was trained in Google Colab using TensorFlow & Keras.

 Features

Transfer Learning using MobileNetV2

Custom dataset selection (3 classes)

Training and validation split

Model saved as .h5 file for reuse

Fully reproducible in Google Colab

 Repository Contents

plant_disease_model.h5 → Trained model file

plant_project_ipynb.ipynb → Google Colab notebook with training and testing code

 How to Use
Option 1 – Run in Google Colab

Open Google Colab

Click File → Upload notebook → select plant_project_ipynb.ipynb

Make sure plant_disease_model.h5 is in the same folder (or upload it to Colab)

Run the cells to:

Load the model

Test the model on sample images

Train further if needed

Option 2 – Clone the Repo
git clone https://github.com/hamza5849/Plant_Disease_Detection.git
cd Plant_Disease_Detection

Then open the notebook in Google Colab or Jupyter Notebook.

 Dataset

The model was trained using PlantVillage Dataset.
Only 3 classes were selected for this project:

Powdery mildew

Healthy

Other

The original dataset is available here

 Requirements

Python 3.x

TensorFlow 2.x

Keras 3.x

OpenCV (opencv-python)

NumPy

Matplotlib

Install packages in Colab using:

!pip install tensorflow keras numpy matplotlib opencv-python
