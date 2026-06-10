# Comprehensive AI Pipeline for Skin Lesion Classification, Localization, and Interpretability

An advanced, production-grade Deep Learning system that combines multi-class computer vision classification, real-time object detection, and explainable AI (XAI) for dermatological clinical support.

---

## 🚀 System Architecture & Capabilities

This pipeline integrates three cutting-edge AI methodologies into a singular inferencing engine:

1. **Multi-Class Classification (MobileNetV2):** Fine-tuned via Transfer Learning on the HAM10000 dataset to classify lesions into major diagnostic categories with an optimized lightweight parameter footprint.
2. **Lesion Localization (YOLOv5):** Integrated real-time object detection architecture to automatically draw precise bounding boxes around localized affected skin areas.
3. **Explainable AI (Grad-CAM):** Generates diagnostic visual heatmaps overlaying the original image, highlighting the exact pixel regions the neural network prioritized during classification to maintain clinical trust.

---

## 🖥️ Interactive Gradio Web Interface

The system features a live web dashboard built with **Gradio** for seamless end-to-end user evaluation.

* **Inputs:** Single-frame dermoscopic skin image uploads (Numpy array ingestion).
* **Outputs:** 
  * 📝 Textbox: Diagnostic label prediction alongside model confidence parameters.
  * 🎯 Visual Box 1: YOLO localized bounding box output.
  * 🔬 Visual Box 2: Grad-CAM attention heatmap visualization.

---

## ⚙️ Local Deployment & Execution

To clone and run this advanced diagnostic interface locally, execute the following block:

```bash
# Clone the repository
git clone [https://github.com/Sobia122/Skin-Cancer-Detection-Deep-Learning.git](https://github.com/Sobia122/Skin-Cancer-Detection-Deep-Learning.git)
cd Skin-Cancer-Detection-Deep-Learning

# Install required framework dependencies
pip install -r requirements.txt

# Execute the integrated Python script / Notebook pipeline
# The interface will spin up locally and generate a public shareable Gradio link.
