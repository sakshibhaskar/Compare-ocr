📝 OCR Comparison: EasyOCR vs Keras-OCR
This project compares the performance of two popular Optical Character Recognition (OCR) tools—EasyOCR and Keras-OCR—on a dataset of document images. The goal is to evaluate their effectiveness in accurately extracting text from various types of images.

📁 Dataset
Type: Document and scene text images

Usage: Input images are processed by both OCR tools to extract text and assess recognition performance.

Note: Dataset loading method may need to be customized depending on your image directory.

🛠️ OCR Tools Compared
1. EasyOCR
Lightweight, ready-to-use OCR library

Supports 80+ languages

Requires minimal setup

Fast and reliable for most use cases

2. Keras-OCR
Modular OCR pipeline using TensorFlow/Keras

Separates detection and recognition stages

More flexible and customizable

Requires additional setup and GPU support for best performance

🔍 Workflow
Load and preprocess images

Apply EasyOCR and Keras-OCR

Extract and visualize text results

Compare outputs qualitatively and quantitatively

Display side-by-side results using plots and overlays

📊 Results
EasyOCR is fast and easy to implement but may struggle with certain fonts or orientations.

Keras-OCR often provides more accurate localization and recognition for complex scenes, especially when tuned properly.

Both tools have unique strengths depending on the use case.

Visual comparisons and examples of extracted text are included in the notebook.

📦 Dependencies
bash
Copy
Edit
pip install easyocr keras-ocr opencv-python matplotlib numpy
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/ocr-comparison.git
cd ocr-comparison
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Compare_OCR_Tools.ipynb
✅ Future Improvements
Add Tesseract OCR for a 3-way comparison

Implement quantitative evaluation using ground truth labels

Integrate confidence scoring and error analysis

Explore multilingual text recognition scenarios

