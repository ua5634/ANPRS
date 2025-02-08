# 🚗 Automatic Number Plate Recognition (ANPR) using OpenCV & Tesseract

## 📌 Project Overview
This project implements **Automatic Number Plate Recognition (ANPR)** using **OpenCV, Tesseract OCR, and Python**. The system detects vehicle number plates from images and extracts the alphanumeric text using **Optical Character Recognition (OCR)**. It can be used for various applications such as:
- Automated toll collection
- Parking management
- Law enforcement
- Smart traffic monitoring systems

## 📷 How It Works
1. Load an image containing a vehicle's number plate.
2. Preprocess the image using OpenCV (grayscale conversion, filtering, and edge detection).
3. Detect the number plate region using contour detection.
4. Extract the number plate and apply **Tesseract OCR** to recognize text.
5. Output the recognized text.

## 🛠️ Tech Stack
The project utilizes the following technologies:

| Tech Stack | Usage |
|------------|-------|
| **Python** | Programming language for implementation |
| **OpenCV** | Image processing and contour detection |
| **Tesseract OCR** | Optical character recognition for text extraction |
| **NumPy** | Numerical operations for image processing |
| **Matplotlib** | Visualization of processed images |
| **Google Colab** | Cloud-based execution environment |
| **Pandas** | Data storage and analysis (for storing recognized text) |

## 🚀 Installation & Setup
Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ANPR-using-OpenCV-Tesseract.git
   cd ANPR-using-OpenCV-Tesseract
   ```
2. Install dependencies:
   ```bash
   pip install numpy opencv-python pytesseract matplotlib pandas imutils
   ```
3. Install Tesseract OCR:
   ```bash
   sudo apt install tesseract-ocr
   ```
4. Run the script:
   ```bash
   python anpr.py
   ```

## 📌 Example Output
- **Input Image:** Car with a visible number plate.
- **Output:** Extracted number plate text (e.g., `MH12DE1433`).

## 🔥 Features
✅ Image pre-processing using OpenCV  
✅ Number plate detection using contour analysis  
✅ Text recognition using Tesseract OCR  
✅ Works with multiple image formats  
✅ Easily extendable for video-based ANPR systems  

## 🛠️ Future Enhancements
- Support for real-time video feed recognition
- Deep learning-based number plate detection for higher accuracy
- Multi-language support using Tesseract

## 📌 License
This project is open-source and licensed under the **MIT License**.

---

👨‍💻 Developed by **Utkarsh** 🚀

