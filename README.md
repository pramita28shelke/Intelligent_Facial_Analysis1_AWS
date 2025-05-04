# Building an Intelligent Facial Analysis System with AWS Services✨

🚀 This project demonstrates how to perform facial analysis using Amazon Rekognition 🌟, a machine learning service provided by AWS. It leverages AWS Lambda for ⚡ serverless execution and Amazon S3 🗂️ for image storage to detect and analyze facial features in real-time. 🎯

  

---

# Features ✨  
- **Facial Detection**: 🖼️ Identify faces in an image stored in an S3 bucket.  
- **Facial Attributes Analysis**: 🧑‍🤝‍🧑 Extract detailed facial attributes like age range, emotions, and more using Amazon Rekognition.  
- **Serverless Execution**: ⚡ The analysis is triggered by an AWS Lambda function.  
- **JSON-Based Insights**: 📝 Results are processed and displayed in JSON format.  

---

# Project Setup 🛠️  

## S3 Bucket Creation 🪣  
- Created an S3 bucket named **aws-facial-rekognition**.  
- Uploaded an image file named **Virat.jpg** for analysis.  

## Lambda Function Configuration 🧑‍💻  
- Created an AWS Lambda function named **DetectFaces**.  
- Assigned the following IAM policies:  
  - ✅ Amazon S3 Read-Only Access  
  - ✅ Amazon Rekognition Read-Only Access  

## Code Implementation 🧑‍💻  
- Used the Python **boto3** library to interact with AWS services.  
- Added logic in the Lambda function to:  
  - 📂 Access the S3 bucket and read the image file.  
  - 👁️ Use Rekognition to detect faces and analyze their attributes.  
  - 📝 Print the results in JSON format.  

---

# Deployment 🚀  
- Deployed the Lambda function.  
- Configured a test event in the AWS Management Console.  
- Verified and redeployed after testing.  

---

# Results 📊  
The project analyzes the uploaded image and provides **JSON output** detailing:  
- 👶 **Age Range** of the person.  
- 😊 **Emotion** (e.g., Happy, Sad).  
- 🎭 Other facial attributes (e.g., eyes open, smiling).  

---

# Technologies Used 🖥️  
- **AWS S3**: 🪣 For storing the image file.  
- **AWS Lambda**: ⚡ For executing the face detection code.  
- **Amazon Rekognition**: 🤖 For analyzing facial details.  
- **Boto3**: 🐍 Python SDK for AWS.  


