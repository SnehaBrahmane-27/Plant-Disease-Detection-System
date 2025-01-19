# Plant Disease Detection System for Sustainable Agriculture

This project aims to provide a machine learning-based solution for detecting plant diseases using leaf images. The system utilizes a Convolutional Neural Network (CNN) to classify plant diseases and offers a web-based platform for real-time diagnosis, empowering farmers to quickly and accurately identify crop diseases.

## Project Overview

- **Problem Statement**: Traditional methods of plant disease detection are time-consuming and require expert knowledge. This project addresses the need for an automated, scalable solution for early detection of plant diseases.
- **Objectives**:
  - Develop a CNN-based model to classify plant diseases using images.
  - Provide a user-friendly, web-based platform for real-time diagnosis.
  - Enable quick identification to reduce crop losses and promote sustainable agriculture.

## Features

- AI-based plant disease classification.
- Real-time image-based disease diagnosis.
- Web-based interface for farmers and agricultural professionals.
- High accuracy model trained on multiple plant species and diseases.

## Technologies Used

- **Programming Language**: Python 3.x
- **Libraries/Frameworks**:
  - TensorFlow/Keras for building and training the CNN.
  - OpenCV for image processing.
  - Streamlit for web application.
  - Pandas, NumPy, Matplotlib for data handling and visualization.
  
## Future Work

- Expand disease coverage to include more plant species.
- Improve image quality handling and real-time diagnosis in the field.
- Develop a mobile application for easier access by farmers.
  
## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/plant-disease-detection
2. Install dependencies:
      pip install -r requirements.txt
3.Import Datasets and Testsets in the folder :
      https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
4. Run the Streamlit web app:
      streamlit run main.py
5. Upload a plant leaf image to receive disease classification.
