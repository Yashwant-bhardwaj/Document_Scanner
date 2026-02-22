# 📄 Smart Document Scanner & Quality Analysis System

A Python-based Smart Document Scanner that enhances, processes, and analyzes real-world document images using advanced image processing techniques.

## 🚀 Project Description

The **Smart Document Scanner** simulates real-world document digitization.

It takes document images (mobile photos, scanned pages, printed sheets) and:

- Detects document boundaries

- Applies perspective transformation

- Enhances brightness and contrast

- Improves readability

- Saves processed outputs

- Displays side-by-side comparison

This project demonstrates practical implementation of Computer Vision concepts using OpenCV.

## 🧠 Key Features

- 📸 Multi-image processing

- 🔍 Edge detection using Canny

- 🧾 Contour detection

- 📐 Perspective transformation

- 🌗 Image enhancement & thresholding

- 💾 Automatic output saving

- 📊 Quality comparison visualization

## 🛠 Technologies Used

- **Python 3.x**

- **OpenCV**

- **NumPy**

- **Matplotlib**

- **scikit-image**

## 📂 Project Structure

document_scanner/

│

├── scanner.py # Main Python script

├── README.md # Project documentation

├── images/ # Input document images

└── outputs/ # Processed output images

## ⚙️ Installation Guide

### Step 1: Install Python

Make sure Python 3.x is installed.

Check version:

python --version

### Step 2: Install Required Libraries

Run the following command:

pip install opencv-python numpy matplotlib scikit-image

## ▶️ How to Run the Project

1. Clone the repository or download the folder.

2. Place your document images inside the images/ folder.

3. Open Command Prompt inside the project directory.

4. Run:

python scanner.py

5. Processed images will be saved in the outputs/ folder.

## 📸 Input Requirements

- Supported formats: .jpg, .jpeg, .png

- Images should contain clear document boundaries

- Avoid extremely blurry images

## 📊 Output

The program generates:

- Enhanced scanned document image

- Perspective corrected document

- Saved output file in outputs/

- Visual comparison between original and processed image

## 💡 Example Use Cases

- Digitizing handwritten notes

- Scanning assignment sheets

- Converting mobile photos to scanned documents

- Improving document clarity for printing

- Educational computer vision demonstration

## 🔮 Future Improvements

- OCR (Text extraction using Tesseract)

- Automatic PDF export

- GUI interface (Tkinter or Streamlit)

- Noise reduction optimization

- Batch PDF generation

## 🧪 Concepts Demonstrated

- Image preprocessing

- Grayscale conversion

- Gaussian blur

- Canny edge detection

- Contour approximation

- Perspective transformation

- Image thresholding

## 👨‍💻 Author

Yashwant

Student | Python Developer | Computer Vision Enthusiast

## 📄 License

This project is created for educational and academic purposes.

