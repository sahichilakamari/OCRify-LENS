# 📄 OCRify LENS

**OCRify LENS** is a lightweight Streamlit application that allows users to upload scanned documents or images (PDF, JPG, PNG), extract text using Optical Character Recognition (OCR), and apply various image featurization techniques to enhance OCR quality.

---

## 🚀 Features

- ✅ Upload scanned documents (PDF, JPG, JPEG, PNG)
- 🧠 **Extract Text from Images** using Tesseract OCR
- 🎨 **Invert Image Colors** for better contrast
- ⚫ **Binarization (Otsu’s Thresholding)** for noise reduction
- 🔄 **Rotate/Deskew Text** for skew correction
- 🔠 **Font Thickness Adjustment** (Dilation/Erosion)

---

## 🖼 Sample UI

![OCRify LENS Interface](![Screenshot 2025-05-22 213230](https://github.com/user-attachments/assets/24a13101-8201-4173-a888-06c7e44da6ed))

---

## 🛠 Tech Stack


- **Frontend/UI**: Streamlit
- **OCR Engine**: Tesseract OCR via `pytesseract`
- **Image Processing**: OpenCV (`cv2`)
- **PDF Handling**: `pdf2image` (optional, if enabled)

---

## 📦 Installation

1. **Clone the repository**  
```bash
git clone https://github.com/your-username/ocrify-lens.git
cd ocrify-lens
