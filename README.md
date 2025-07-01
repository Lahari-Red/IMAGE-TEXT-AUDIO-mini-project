# IMAGE-TEXT-AUDIO-mini-project
# 🖼️📢 Image to Speech using OCR and Text-to-Speech (TTS)

This project extracts text from an image using **OCR (Optical Character Recognition)** and then converts that text into spoken audio using **Google Text-to-Speech (gTTS)**.

---

## 📌 Features

- Upload any image with readable text (e.g., scanned documents, posters)
- Automatically extract printed text using `pytesseract`
- Convert extracted text to audio using `gTTS`
- Play or download the audio file directly in Google Colab

---

## 📁 Files Used

- `Picture1.png`: Example input image with text
- `hello.mp3`: Generated audio output from extracted text

---

## 🔧 Requirements

Google Colab (no local setup needed)

Install required packages:
```bash
!apt update
!apt install -y tesseract-ocr
!pip install pytesseract gTTS
