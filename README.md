# Billionaire-Image-Classifier

A fully fledged, ready-to-go machine learning classification project deployed on AWS cloud.

## Billionaire Image Classifier - AWS Deployed

This project is a **Billionaire Image Classifier** that uses **Machine Learning** to identify images of famous billionaires. It is built with **Python**, **OpenCV**, and **Scikit-Learn**, and deployed on **AWS Cloud** with both a **backend API** and a **frontend UI**.

## Features
- Detects and crops faces using **OpenCV's Haar cascades**.
- Extracts features using **Wavelet Transform (w2d)**.
- Uses a **trained Machine Learning model** for classification.
- Provides a **web-based UI** for users to upload images and get predictions.
- Deployed on **AWS Cloud** for high availability.


## Technologies Used
- **Python** (Backend)
- **Flask** (REST API)
- **OpenCV** (Image Processing)
- **Scikit-Learn** (ML Model)
- **Joblib** (Model Serialization)
- **NumPy** (Data Handling)
- **AWS EC2 (Ubuntu AMI)** (Cloud Hosting)
- **AWS S3** (Artifact Storage)
- **AWS Lambda** (Serverless Functions)
- **React.js** (Frontend UI)

---

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/billionaire-image-classifier.git
cd billionaire-image-classifier
```

### 2. Create a Virtual Environment (Optional)
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Run the Server Locally
```sh
python app.py
```
The API will be available at `http://127.0.0.1:5000/`.

---

## Deployment on AWS
This project is **deployed on AWS** using:
- **EC2 (Ubuntu AMI)** for hosting the backend.
- **S3** for storing model artifacts.
- **Lambda Functions** for processing requests.
- **AWS API Gateway** for API exposure.



## Usage
1. Open the **web-based UI**.
2. Upload an image of a billionaire.
3. The model processes the image and returns:
   - The **predicted billionaire** name.
   - **Confidence scores** for each class.
   - A visualization of the cropped face (if detected).

## License
This project is licensed under the **MIT License**.

