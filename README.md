# Palm Recognition Biometric System
<img width="973" alt="Screenshot 2023-06-30 at 12 19 07 PM" src="https://github.com/Smith-S-S/Contactless-Palm-Recognition-System/assets/80092760/8535a901-f5d2-42e1-be10-2bd38b8bdded">


## Overview

This repository contains the implementation of a Contactless Palm Recognition Biometric System. The system utilizes state-of-the-art palm recognition technology to provide secure and convenient biometric authentication. It offers a contactless and user-friendly approach for various applications.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Image Processing Techniques](#Image-Processing-Techniques)
- [Preprocessing](#Preprocessing)
- [Feature Extraction](#Feature-Extraction)
- [Installation](#installation)
- [Usage](#usage)
- [Technology Stack](#technology-stack)


## Project Description

The Palm Recognition Biometric System is designed to identify and authenticate individuals based on their unique palmprint patterns. It offers a secure and convenient way to access various services and systems without the need for physical contact.

## Features

- Contactless Palmprint Capture: Utilize a camera to capture palmprint images without physical contact.
- Real-time Recognition: Achieve real-time palmprint recognition for seamless and efficient authentication.
- User-Friendly Interface: Provide an intuitive user interface for easy enrollment and authentication.

## Image Processing Techniques

The Palm Recognition Biometric System leverages advanced image processing techniques to achieve accurate and reliable palmprint recognition. These techniques play a crucial role in extracting relevant features from palmprint images and performing efficient matching.

### Preprocessing

- Image Resizing: Resize captured palmprint images to a standardized resolution for consistent feature extraction.
- Contrast Enhancement: Apply techniques like Histogram Equalization and Contrast Limited Adaptive Histogram Equalization (CLAHE) to improve image contrast and enhance palmprint details.

### Feature Extraction

- Region of Interest (ROI) Detection: Locate and extract the palm region from the captured image using techniques like Object Detection to find the palm first and crop the palm.

## Installation

1. Clone this repository: `git clone https://github.com/yourusername/palm-recognition.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Run the application: `python main.py`

## Technology Stack

- Python: Programming language used for development.
- OpenCV: Library for computer vision and image processing.
- Deep Learning: Leveraged for palmprint feature extraction and recognition.
- GUI Library: Pyqt5 to create an interactive user interface.

