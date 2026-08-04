# Computer Vision & Artificial Intelligence (ITAI 1378)

## Course Overview
This directory houses my engineering laboratories, architectural design blueprints, and capstone software packages completed during my studies in the Applied AI and Robotics program. The coursework covers the entire computer vision pipeline: low-level pixel manipulation, spatial matrix operations, classical machine learning image classification, deep neural networks, Convolutional Neural Networks (CNNs), state-of-the-art object detection/segmentation, and multi-modal Vision-Language Models (VLMs).

---

## Core Projects & Laboratory Index

### 1. Project Foundations & Research Drafts
*   **Directory Path**: [./Midterm_Final_Project_Individual_Portfolio_Instructions/](./Midterm_Final_Project_Individual_Portfolio_Instructions/)
    *   Contains the initial technical proposals, midterm blueprint designs (`MD_Dang_Cuong_ITAI1378.pdf`), and foundational framework instructions that served as the baseline development premise for the final system.

### 2. Capstone Project: SentinelCleanAIFN Deployed Production Build
*   **Directory**: [./FINAL PROJECT/](./FINAL%20PROJECT/)
*   **Problem Statement**: Automated visual environmental quality control requires the isolation of targets, removal of scene artifacts, and real-time detection of anomalies in varying lighting conditions.
*   **Approach & Execution**:
    *   Designed and deployed an end-to-end vision processing pipeline utilizing fine-tuned YOLOv11 nano detectors to recognize real floor hazard anomalies at an ultra-low latency scale.
    *   Formulated detailed architectural diagrams, dual-model conditional segmentations, and execution metrics hosted within the local documentation layout (`FINAL PROJECT/docs/presentation.pdf` and `FINAL PROJECT/docs/AI_usage_log.md`).
    *   Isolated key sample outputs, test split predictions, and authentic performance matrix graphs stored directly within the repository `FINAL PROJECT/results/` folder to prove successful background noise removal.

### 2. Computer Vision Lifecycle Laboratories

*   **[Module 01](./Module%2001%20Welcome%20-Computer%20Vision%20Fundamentals/) & [Module 02](./Module%2002%20Image%20Fundamentals%20and%20Processing/)**: Vision Tooling & Pixel Matrices
    *   Configured core development tools and built functional image processing pipelines. Implemented color-space transformations (RGB, HSV, Grayscale), edge detection thresholds, and analytical matrix modifications.
*   **[Module 03](./Module%2003%20Machine%20Learning%20for%20Computer%20Vision/)**: Classical ML for Vision Tasks
    *   Leveraged Support Vector Machines (SVM) and classical classifiers on subset image data (CIFAR-10) to benchmark non-deep-learning image categorization techniques.
*   **[Module 04](./Module%2004%20ITAI%201378%20Basics%20of%20Neural%20Networks/)**: Foundations of Deep Learning
    *   Built early neural networks, graphed network layers, and mapped out basic optimization paths, learning rates, and weights.
*   **[Module 05](./Module%2005%20Convolutional%20Neural%20Networks/)**: Convolutional Architectures
    *   Engineered a deep Convolutional Neural Network (CNN) from scratch to solve the highly non-linear "Chihuahua or Muffin" classification challenge. Analyzed pooling layers, feature maps, and model loss curves.
*   **[Module 06](./Module%2006%20Detection%20and%20segmentation/)**: Advanced Detection & Segmentation
    *   Implemented state-of-the-art YOLO object detection algorithms, regional neural networks, and boundary segmentation mapping over complex visual frames.
*   **[Module 08](./Module%2008%20Visual%20Language%20Models/)**: Vision Transformers (ViTs) & Visual Language Models (VLMs)
    *   Deployed cutting-edge multi-modal architectures using the `SmolVLM-500M-Instruct` foundation model accelerated via cloud T4 GPU runtimes. 
    *   Implemented zero-shot image captioning, contextual image-to-text querying, and visual dialogue pipelines to establish open-ended conversation layers directly with complex scene matrices.

---

## Technical Arsenal
*   **Languages**: Python (3.x)
*   **Core Vision Libraries**: OpenCV (`cv2`), PIL, Matplotlib, Transformers
*   **Deep Learning Frameworks**: TensorFlow, Keras, PyTorch, Hugging Face SDK
*   **Evaluation Frameworks**: Intersection over Union (IoU), Confusion Matrices, Loss/Accuracy Curves, Precision-Recall Sliders, Open-Ended VLM Benchmarks

---

## How to Execute the Notebooks
1. Ensure your workspace includes standard dependencies: `pip install numpy opencv-python tensorflow torch torchvision matplotlib transformers accelerate`.
2. Navigate into the targeted module or final project folder.
3. Open the `.ipynb` notebook file inside Google Colab or your local Jupyter server.
4. *Note: All Jupyter notebooks have been pre-run with cached outputs, plots, and graphs fully visible on the GitHub web viewer.*
