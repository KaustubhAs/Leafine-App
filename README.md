# Leafine: Plant Disease Detection Application

[cite_start]**Leafine** is a mobile application designed to revolutionize agriculture and environmental monitoring by providing real-time, non-intrusive, and highly accurate plant health assessments[cite: 490, 497]. [cite_start]Using advanced Artificial Intelligence, Deep Learning (CNN), and image processing, Leafine helps farmers and researchers detect plant diseases early to reduce crop losses and pesticide use[cite: 326, 503].

## 📖 Abstract
[cite_start]In a world facing climate change and increasing pest infestations, early disease identification is critical for food security[cite: 496, 506]. [cite_start]Leafine utilizes a trained deep learning model (VGG-16 architecture) to analyze images of crop leaves and detect subtle visual signals of disease, such as color variations and lesions[cite: 497, 499, 628]. [cite_start]The goal is to empower stakeholders with actionable insights for better crop management and resource allocation[cite: 500].

## ✨ Key Features
* [cite_start]**Real-time Detection:** Instantly analyzes leaf photos taken via a mobile camera[cite: 516].
* [cite_start]**High Accuracy:** Built on the VGG-16 CNN architecture for robust image classification[cite: 628].
* [cite_start]**User-Friendly Interface:** Simple Android interface designed for farmers and non-technical users[cite: 500, 656].
* [cite_start]**Scalable & Flexible:** Suitable for various agricultural, horticultural, and ecological applications[cite: 501].
* [cite_start]**Actionable Insights:** Identifies specific diseases (e.g., Common Rust in Corn, Black Rot in Grape/Apple)[cite: 456].

## 🏗️ System Architecture & Methodology
The system follows a pipeline of data collection, pre-processing, and classification using a Convolutional Neural Network (CNN).

![Block Diagram of Proposed System](Images/Block dig of Arch.png)
[cite_start]*Fig 1. Block Diagram of Proposed System [cite: 642]*

### Steps involved:
1.  [cite_start]**Data Collection:** Aggregation of a large dataset of healthy and diseased plant images[cite: 585].
2.  [cite_start]**Pre-processing:** Resizing images (e.g., 224x224), normalizing pixel values, and data augmentation (rotation, flipping)[cite: 587, 588].
3.  [cite_start]**Model Architecture:** * Base: Pre-trained **VGG-16** model (ImageNet weights)[cite: 589].
    * [cite_start]Custom Layers: Added for binary/multi-class classification (Healthy vs. Diseased)[cite: 591].
4.  [cite_start]**Training:** Optimized using binary cross-entropy loss and Adam/SGD optimizers[cite: 593].
5.  [cite_start]**Deployment:** The trained model is deployed on an Android application for live detection[cite: 605].

## 🛠️ Technology Stack

### Software Requirements
* [cite_start]**Language:** Python 3.9 [cite: 700]
* [cite_start]**Deep Learning Frameworks:** * TensorFlow (Foundational library) [cite: 701]
    * [cite_start]Keras (High-level neural networks library) [cite: 702]
* [cite_start]**IDE:** PyCharm [cite: 703]

### Hardware Requirements
* [cite_start]**Platform:** Android Operating System [cite: 705]
* [cite_start]**Memory:** Minimum 8 GB RAM recommended [cite: 706]

## 📱 Mobile Application
The application allows users to capture or upload an image of a plant leaf. The system processes the image and returns a prediction with the disease name and confidence score.

![Mobile Application Screenshots](path/to/your/app_screenshots.png)
[cite_start]*Fig 6. Mobile Application Interface showing detection of Black Rot and Common Rust [cite: 456, 457]*

## 📊 Results
[cite_start]The model has demonstrated impressive performance metrics, showing high accuracy, precision, recall, and F1-scores in differentiating between healthy and diseased plants[cite: 709].

* [cite_start]**Training vs Validation:** The model shows consistent convergence in loss and accuracy graphs[cite: 671, 685].
* **Sample Predictions:**
    * *Corn (Maize):* Common Rust
    * *Grape:* Black Rot
    * *Apple:* Black Rot
    [cite: 456]

## 🤝 Acknowledgements
[cite_start]Special thanks to the Department of Computer Engineering at SIES Graduate School of Technology, University of Mumbai, and our project guides for their support[cite: 494, 463].

## 📚 References
This project references studies on CNNs and plant disease detection, including:
1.  [cite_start]*Plant Disease Detection using Image Processing* (2020)[cite: 365].
2.  [cite_start]*Plant Disease Detection Using CNN* (2022)[cite: 373].
3.  [cite_start]*Deep learning models for plant disease detection and diagnosis* (2018)[cite: 384].

*(See full report for complete bibliography)*
