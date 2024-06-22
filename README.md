## Third Eye: Real-time Object Recognition System

This repository contains the code and resources for a real-time object recognition system named Third Eye, built using a Raspberry Pi and camera.

### Project Description

Third Eye is designed to:

* Detect a wide range of objects (up to 70) with high accuracy (98%).
* Improve environmental awareness and object classification for various applications.
* Enhance accessibility for visually impaired users by converting detected objects into audible descriptions using Google's Neural Network Text-to-Speech API.

### Key Features

* **Real-time object detection:** Leverages a pre-trained YOLO v3 model for efficient object recognition in real-time.
* **High accuracy:** Achieves an accuracy of 98% in detecting a variety of objects.
* **Optimized performance:** Fine-tuned YOLO v3 model and utilizes hardware acceleration for faster processing on Raspberry Pi.
* **Accessibility integration:** Integrates Google's Text-to-Speech API to provide audible descriptions of detected objects.

### Getting Started

This project requires a Raspberry Pi with a camera module and software libraries like OpenCV and TensorFlow Lite.

**Prerequisites:**

* Raspberry Pi with camera module
* Raspbian OS installed
* Python 3.x
* OpenCV library

**Instructions:**

1. **Clone the repository:**

```bash
git clone https://github.com/Tharanitharan-M/Third-Eye.git
```

2. **Install dependencies:**

   * Follow the installation instructions for OpenCV on Raspberry Pi.

3. **(Optional) Fine-tune the model:**

   * You can further improve accuracy by fine-tuning the pre-trained model on your own custom dataset (refer to YOLO v3 documentation).

4. **Run the application:**

   * Run the script (`main.py`) to start the object recognition system.
