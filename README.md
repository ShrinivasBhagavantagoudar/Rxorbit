# RxOrbit – From Doctor’s Notes to Patient Clarity 🩺📄

RxOrbit is an AI-powered healthcare assistant designed to analyze **handwritten medical prescriptions** and **printed diagnostic reports**, transforming them into **structured, readable, and patient-friendly information**.  
The system leverages **OCR, NLP, and multimodal AI reasoning**, and is delivered through a **Telegram bot interface** for easy real-time access.

---

## 📌 Project Overview

In many healthcare systems, handwritten prescriptions and complex diagnostic reports often lead to:
- Misinterpretation of medicines
- Incorrect dosage intake
- Poor patient understanding and adherence

**RxOrbit** bridges the gap between doctors and patients by automatically extracting, interpreting, and explaining medical documents in a simple and accessible format.

---

## 🎯 Objectives

- Analyze handwritten prescriptions and printed diagnostic reports
- Extract accurate medical text using OCR
- Interpret medical content using AI and NLP
- Generate structured summaries of:
  - Medicine names
  - Dosage and timing
  - Diagnostic test values and status
- Provide outputs in **text, PDF, and audio**
- Enable interaction via a **Telegram bot**
- Support multilingual output (English & Kannada)

---

## 🏗️ System Architecture

**RxOrbit Pipeline:**
1. User uploads prescription/report via Telegram
2. OCR extracts text (PaddleOCR / Tesseract)
3. AI model performs contextual analysis
4. GRPO-inspired inference selects best output
5. Structured result delivered as:
   - Text summary
   - PDF report
   - Audio explanation (TTS)

---

## 🧠 Technologies Used

### Programming & Frameworks
- Python 3.10+
- pyTelegramBotAPI (Telebot)

### OCR & Image Processing
- PaddleOCR (handwritten text)
- Tesseract OCR (printed reports)
- Pillow (PIL)
- pdf2image

### AI & NLP
- PyTorch
- Transformers
- Vision-enabled multimodal AI
- GRPO-inspired inference optimization

### Utilities
- pandas, numpy, regex
- reportlab (PDF generation)
- gTTS (Text-to-Speech)
- python-dotenv

---

## ⚙️ Hardware & Software Requirements

### Hardware
- Intel i5 / AMD equivalent or higher
- Minimum 8 GB RAM (16 GB recommended)
- Optional NVIDIA GPU with CUDA
- Stable Internet connection

### Software
- Windows / Linux / macOS (64-bit)
- Python 3.10 or above
- Telegram account

---

## 🚀 Features

- ✅ Handwritten prescription analysis
- ✅ Diagnostic report interpretation
- ✅ Automatic document classification
- ✅ Multilingual support (English & Kannada)
- ✅ Audio explanation using TTS
- ✅ Downloadable structured PDF reports
- ✅ Privacy-preserving image preprocessing
- ✅ Telegram-based real-time interaction

---

## 📊 Performance Highlights

- **Document Classification Accuracy:** 94%
- **ROC-AUC Score:**  
  - Prescription: 0.97  
  - Medical Report: 0.93  
  - Unknown: 0.97
- **Average Response Time:** ~20 seconds

---

## 🔐 Privacy & Ethics

- Personal identifiers are masked before processing
- Sensitive data is not permanently stored
- Ethical AI practices followed
- Designed for patient safety and clarity

---

## 📂 Project Structure (Sample)

