# DeepDetect – Deepfake Image Detection

## Overview
DeepDetect is a deep learning project focused on detecting deepfake images using
convolutional neural networks (CNNs). Multiple state-of-the-art architectures
were trained and evaluated to compare performance and identify the
best-performing models.

## Project Structure
The repository is organized to clearly separate training experiments from the
final selected models:
`
BestModels/
├── BestModels.ipynb
└── README.md

TrainingModels/
├── DeepDetect_EfficientNetB0.ipynb
├── DeepDetect_ResNet50_V1.ipynb
├── DeepDetect_ResNet50_V2.ipynb
├── DeepDetect_Xception.ipynb
└── README.md

DeepDetect_Report.pdf
DeepDetect_Presentation.pdf
`

## Dataset
The dataset used in this project consists of real and fake images for deepfake
detection.

Due to its large size, the dataset is hosted externally on Google Drive:

🔗 **Dataset link:**  
https://drive.google.com/file/d/1sEsIU1cXjmf4skqSqkfGPIdad4gZHV5j/view?usp=sharing

## Models and Experiments
The following deep learning architectures were implemented and trained:

- EfficientNetB0  
- ResNet50 (Version 1)  
- ResNet50 (Version 2)  
- Xception  

Each notebook includes:
- Data loading and preprocessing
- Model architecture definition
- Training and validation
- Performance evaluation

## Best Models
The `BestModels/` directory contains the final selected models based on
comparative evaluation and performance metrics.

## Results and Evaluation
Model performance was evaluated using accuracy and validation metrics.
A detailed comparison and discussion of results are available in the report
and presentation files.

## Reports and Documentation
- **DeepDetect_Report.pdf** – Detailed technical report
- **DeepDetect_Presentation.pdf** – Project presentation summarizing methodology
  and results

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook
