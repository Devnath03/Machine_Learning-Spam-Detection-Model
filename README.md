
# Email & Document Spam Detection System

## Overview

This repository provides a complete, production-ready solution for detecting spam emails using machine learning. It includes data analysis, feature engineering, model training, evaluation, deployment, and a web interface for real-time predictions. The project is designed for clarity, reproducibility, and practical use, following global standards and best practices.

## Features

- Labeled email dataset (`emails.csv`)
- Jupyter notebooks for step-by-step workflow and testing (`Email_Spam_Detection.ipynb`, `Sample_Test.ipynb`)
- Flask web app for user-friendly spam detection (text and file upload)
- Support for .txt, .pdf, and .docx file uploads
- Pre-trained model (`model.pickle`) for instant inference
- Modular, scalable, and reproducible code
- Clear documentation and comments for each step

## Standard Methods & Workflow

### 1. Data Preprocessing
- Cleaning and transforming raw email text
- Removing duplicates and handling missing values

### 2. Feature Engineering
- Extracting features such as word frequencies, TF-IDF, and n-grams
- Using `CountVectorizer` for text vectorization

### 3. Model Training
- Splitting data into training and test sets
- Training a Naive Bayes classifier using scikit-learn
- Building a pipeline for streamlined training and prediction

### 4. Model Evaluation
- Evaluating performance with accuracy, precision, recall, and confusion matrix
- Visualizing results with plots

### 5. Model Serialization
- Saving trained models with pickle for reuse and deployment

### 6. Deployment & Inference
- Flask web app for real-time spam detection
- Supports direct text input and file uploads (.txt, .pdf, .docx)
- Instant predictions using the pre-trained model

## Folder Structure

- `emails.csv` — Labeled dataset
- `Email_Spam_Detection.ipynb` — Main notebook for analysis and model building
- `Sample_Test.ipynb` — Notebook for testing the model on new samples
- `main.py` — Flask web application for spam detection
- `model.pickle` — Pre-trained model
- `templates/index.html` — Web app interface
- `uploads/` — Folder for uploaded files

## How to Use

1. **Install dependencies:**
	- Install required Python packages as listed in the notebooks and `main.py` (e.g., pandas, scikit-learn, flask, docx, PyPDF2).
2. **Explore the Jupyter Notebook:**
	- Open `Email_Spam_Detection.ipynb` for a complete workflow from data loading to model evaluation.
3. **Test with new samples:**
	- Use `Sample_Test.ipynb` to validate the model on unseen emails.
4. **Run the web app:**
	- Start the Flask app with `python main.py` and use the browser interface for spam detection.
5. **Experiment with data:**
	- Modify or extend `emails.csv` to improve or adapt the spam filter.

## Advanced Features

- Modular code for easy extension and integration
- Scalable design for large datasets and real-world deployment
- Support for multiple file formats in uploads

## Actions Overview

01. Landing Pages
2. 
<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/3b686fc6-f1ee-4d9e-a85b-61c86d11f29f" />

<img width="1912" height="822" alt="image" src="https://github.com/user-attachments/assets/7d1a5671-5539-45a9-8552-95607b3b6449" />

<img width="1918" height="745" alt="image" src="https://github.com/user-attachments/assets/c1039851-18b5-4a7b-8593-ae8101b7b15c" />

02. Uploading & Typing Methods
   
<img width="1903" height="806" alt="image" src="https://github.com/user-attachments/assets/92b73af6-b56e-4359-97d1-23745443b12f" />

- Spam Alert
  
<img width="1890" height="918" alt="image" src="https://github.com/user-attachments/assets/e02267cd-0a72-439b-919e-452a4f87f175" />

- No Spam Alert
  
<img width="1896" height="907" alt="image" src="https://github.com/user-attachments/assets/46bdb396-69cd-4e00-94de-90f9ecc81e96" />

-- Document Uploading

<img width="1900" height="906" alt="image" src="https://github.com/user-attachments/assets/8b0b134f-fc47-4cf4-8082-608024cddf5d" />

-- Error Alerting

<img width="1902" height="911" alt="image" src="https://github.com/user-attachments/assets/02e27581-92ed-4c8b-a17c-6aee8780d46c" />

03. Detection Methods
   
<img width="1902" height="911" alt="image" src="https://github.com/user-attachments/assets/6740ad6e-b9c6-46d0-973b-b40054843269" />

---- Simple Overview about the process of the model in via the simple UI Interface. -----

## Learning Outcomes

By working through this project, you will:
- Understand spam detection using machine learning
- Gain experience in text preprocessing and feature engineering
- Learn to train, evaluate, and deploy classification models
- Build and deploy a web application for real-time inference
- Apply best practices for reproducibility and deployment

---

This project is part of the Machine Learning End-to-End Models suite, providing a practical and modern approach to building intelligent systems for real-world applications.
