# 📝 Text Detection Using OpenCV & EasyOCR

This project performs text detection and recognition on images using OpenCV and EasyOCR. It identifies text regions in an image, draws bounding boxes around them, and annotates the detected text directly on the image.

# 🧰 Requirements
Python 3.6+
OpenCV
EasyOCR
matplotlib
PyTorch (required by EasyOCR)

# 📦 Install dependencies
'''
pip install opencv-python easyocr matplotlib torch torchvision torchaudio
'''

# 📂 Project Structure
Text-Detection-UsingOpenCV/
├── main.py               # Main script (your shared code)
├── 2.jpg                 # Sample input image
└── README.md             # This file

# 🧠 How It Works
Loads an input image using OpenCV.
Uses EasyOCR to detect and recognize text in the image.
Draws bounding boxes and overlays the recognized text on the image.
Displays the final annotated image using matplotlib.

# 📌 Notes
Works with multiple languages — change ['en'] to any supported language code.
You can disable GPU by setting gpu=False in easyocr.Reader(...) if CUDA is not available.
Ideal for document analysis, number plate reading, signboard text recognition, etc.
