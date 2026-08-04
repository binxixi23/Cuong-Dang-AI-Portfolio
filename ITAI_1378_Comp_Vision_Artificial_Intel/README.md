# Computer Vision & Artificial Intelligence (ITAI 1378)

## Course Overview
This directory houses my engineering laboratories, architectural design blueprints, and capstone software packages completed during my studies in the Applied AI and Robotics program. The coursework covers the entire computer vision pipeline: low-level pixel manipulation, spatial matrix operations, classical machine learning image classification, deep neural networks, Convolutional Neural Networks (CNNs), and real-time object detection/segmentation systems.

---

## Core Projects & Laboratory Index

### 1. Capstone Project: SentinelClean System Development
* **Directory**: [./FINAL-PROJECT/](./FINAL-PROJECT/)
* **Problem Statement**: Automated visual environmental quality control requires the isolation of targets, removal of scene artifacts, and real-time detection of anomalies in varying lighting conditions.
* **Approach**:
  * Designed an end-to-end vision processing pipeline mapping raw sensor input to structured segmentations.
  * Formulated detailed architectural diagrams and execution metrics hosted within the local documentation (`MD_Dang_Cuong_ITAI1378.pdf`).
  * Isolated key sample outputs, test images, and visual evidence of successful background noise removal.

### 2. Computer Vision Lifecycle Laboratories
* **[Module 01](./Module%2001%20Welcome%20-Computer%20Vision%20Fundamentals/) & [Module 02](./Module%2002%20Image%20Fundamentals%20and%20Processing/)**: Vision Tooling & Pixel Matrices
  * Configured core development tools and built functional image processing pipelines. Implemented color-space transformations (RGB, HSV, Grayscale), edge detection thresholds, and analytical matrix modifications.
* **[Module 03](./Module%2003%20Machine%20Learning%20for%20Computer%20Vision/)**: Classical ML for Vision Tasks
  * Leveraged Support Vector Machines (SVM) and classical classifiers on subset image data (CIFAR-10) to benchmark non-deep-learning image categorization techniques.
* **[Module 04](./Module%2004%20ITAI%201378%20Basics%20of%20Neural%20Networks/)**: Foundations of Deep Learning
  * Built early neural networks, graphed network layers, and mapped out basic optimization paths, learning rates, and weights.
* **[Module 05](./Module%2005%20Convolutional%20Neural%20Networks/)**: Convolutional Architectures
  * Engineered a deep Convolutional Neural Network (CNN) from scratch to solve the highly non-linear "Chihuahua or Muffin" classification challenge. Analyzed pooling layers, feature maps, and model loss curves.
* **[Module 06](./Module%2006%20Detection%20and%20segmentation/)**: Advanced Detection & Segmentation
  * Implemented state-of-the-art YOLO object detection algorithms, regional neural networks, and boundary segmentation mapping over complex visual frames.

---

## Technical Arsenal
* **Languages**: Python (3.x)
* **Core Vision Libraries**: OpenCV (`cv2`), PIL, Matplotlib
* **Deep Learning Frameworks**: TensorFlow, Keras, PyTorch
* **Evaluation Frameworks**: Intersection over Union (IoU), Confusion Matrices, Loss/Accuracy Curves, Precision-Recall Sliders

---

## How to Execute the Notebooks
1. Ensure your workspace includes standard dependencies: `pip install numpy opencv-python tensorflow torch torchvision matplotlib`.
2. Navigate into the targeted module or final project folder.
3. Open the `.ipynb` notebook file inside Google Colab or your local Jupyter server.
4. *Note: All Jupyter notebooks have been pre-run with cached outputs, plots, and graphs fully visible on the GitHub web viewer.*
