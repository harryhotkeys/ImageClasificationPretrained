Markdown
# Modernized AI Image Classifier GUI

A sleek, responsive desktop application built with Python and Tkinter (`ttk`) that leverages a pretrained **ResNet-18** model to classify images across all 1000 ImageNet categories.

---

## Features

* **Pretrained ResNet-18:** Powered by `torchvision` for fast and accurate image predictions[cite: 1].
* **Top-5 Predictions:** Displays the highest-matching class alongside confidence percentages and ImageNet indices[cite: 1].
* **Batch Processing:** Classify a single image or an entire folder with an automated progress bar and ETA tracking[cite: 1].
* **Modern UI:** Clean layout utilizing dark-mode custom styling, custom typography, and native `ttk` widgets[cite: 1].
* **Thread-Safe & Responsive:** Runs inference in background threads so the application UI never freezes while working[cite: 1].

---

## Requirements

Install the necessary dependencies using pip[cite: 1]:

```bash
pip install torch torchvision pillow
How to Run
Clone or download this repository.

Ensure you are in the directory containing the source code.

Run the application script:

Bash
python ImageClassificationPretrained.py
Note: On your first launch, the application will automatically download the official ImageNet label mappings and cache them locally as imagenet_labels.json for future offline use.

Project Structure
ImageClassificationPretrained.py — The core application source code containing both the modern UI layout and the machine learning inference logic.

images/ — The default directory scanned for batch folder classification[cite: 1].

imagenet_labels.json — Automatically generated cache file containing the 1000 ImageNet class mappings.
