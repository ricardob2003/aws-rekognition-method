#AWS Rekognition Label Detection with Visualization

##This Python project demonstrates how to use Amazon Rekognition to detect labels in images stored in an S3 bucket. It fetches images, analyzes them using Rekognition's detect_labels API, and visualizes the detected labels and bounding boxes directly on the image using Matplotlib.

Features:
- Integration with Amazon Rekognition to detect labels and their confidence levels.
- Image retrieval from an S3 bucket using Boto3.
- Visualization of bounding boxes and labels over the image using Matplotlib.

###How to Use:
-Configure your AWS credentials and ensure the IAM user has the necessary permissions for Rekognition and S3.
-Update the S3 bucket name and image file in the script.
-Run the script to display the image with labeled bounding boxes.

###Requirements:
-Python 3.x
-AWS SDK for Python (Boto3)
-Matplotlib
-Pillow
