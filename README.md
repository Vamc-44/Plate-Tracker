# Plate-Tracker

Abstract – The goal of this project is to increase the effectiveness of parking management by creating a foundational system for text extraction and license plate detection. The system recognizes and extracts text from photos of license plates by using digital image processing techniques. After capturing the image and preprocessing it to improve its quality, the license plate region is precisely detected. Text is then extracted from the designated Region of Interest (ROI) using optical character recognition (OCR). This project establishes the foundation for parking facility automated vehicle identification. By integrating with the current parking management infrastructure, facility managers and patrons will benefit from less manual intervention, lower operating expenses, and an enhanced user experience. This expandable solution offers a strong foundation for upcoming improvements to automated car entry and exit procedures.

## Features

- Detects license plates in images using a pre-trained deep learning model.
- Extracts text from detected license plates using PyTesseract.
- Visualizes results with bounding boxes around detected plates.
- Provides preprocessing techniques to enhance image quality for OCR.

InceptionNetV2:

A convolutional neural network (CNN) called Inception-ResNet-v2 is capable of classifying images into 1,000 different object categories. A portion of the ImageNet database, which has more than a million photos, is used to train Inception-ResNet-v2. Images of various animals as well as keyboards, mice, and pencils can be classified 
by it. Based on the Inception family of architectures, Inception-ResNet-v2 employs residual connections rather than filter concatenation.

![image](https://github.com/user-attachments/assets/4468fbb2-0234-44b1-b965-edacc19f4d60)

PyTesseract is a Python wrapper for Google's Tesseract OCR Engine that makes it easier for Python programs to extract text from images. It is well known for its capacity to transform handwritten or printed text into machine-readable data, and it supports a number of image formats, including TIFF, PNG, and JPEG. By adding features like better language detection and font orientation recognition, PyTesseract improves Tesseract's core functionality. It is excellent at processing images using preprocessing methods like contrast enhancement and noise reduction, which are essential for enhancing OCR accuracy in low-quality images.

The Plate Tracker project effectively created an automated system for recognizing license plates that combines deep learning and sophisticated image processing techniques. Through the use of transfer learning and the InceptionResNetV2 architecture, we were able to detect and locate license plates with strong performance under a variety of circumstances. A carefully selected dataset was used to train the model, and XML annotations were used to provide exact bounding box coordinates. 

The system's capabilities were further improved by the use of PyTesseract for text extraction, which made it possible to accurately recognize alphanumeric characters from detected license plates. We proved the efficacy of fusing cutting-edge deep learning models with conventional OCR methods using a methodical approach that comprised data preprocessing, model training, and evaluation.

The findings show that our system is capable of accurately detecting and extracting license plate information, which qualifies it for use in automated vehicle identification, traffic management, and security surveillance applications. Future research could examine additional ways to improve model performance, like integrating more sophisticated architectures or adding more preprocessing methods to deal with difficult environmental circumstances.
![image](https://github.com/user-attachments/assets/892c8954-e4b0-4981-848d-d3b4ec8240d6)
![image](https://github.com/user-attachments/assets/7537ca44-f842-4d5b-b24e-a9bc089ac810)
