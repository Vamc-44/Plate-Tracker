# Plate-Tracker

Abstract – The goal of this project is to increase the effectiveness of parking management by creating a foundational system for text extraction and license plate detection. The system recognizes and extracts text from photos of license plates by using digital image processing techniques. After capturing the image and preprocessing it to improve its quality, the license plate region is precisely detected. Text is then extracted from the designated Region of Interest (ROI) using optical character recognition (OCR). This project establishes the foundation for parking facility automated vehicle identification. By integrating with the current parking management infrastructure, facility managers and patrons will benefit from less manual intervention, lower operating expenses, and an enhanced user experience. This expandable solution offers a strong foundation for upcoming improvements to automated car entry and exit procedures.

## Features

- Detects license plates in images using a pre-trained deep learning model.
- Extracts text from detected license plates using PyTesseract.
- Visualizes results with bounding boxes around detected plates.
- Provides preprocessing techniques to enhance image quality for OCR.
