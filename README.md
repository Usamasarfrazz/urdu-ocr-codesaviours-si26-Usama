# Urdu OCR — A Fine-Tuned TrOCR Model for Urdu Text Recognition

## Project Description

This project aims to extract Urdu text from images using Microsoft's TrOCR model. The model was fine-tuned and tested during the Code Saviours ML/AI Internship (SI-26).

---

# Problem Statement

Urdu OCR is difficult because Urdu has:

- Different fonts (Nastaliq, Naskh)
- Connected characters
- Handwritten and printed text
- Different backgrounds

This project helps convert Urdu images into digital text.

Example use cases:

- Digitizing books
- Reading newspapers
- Document processing
- Education

---

# How It Works

The project uses Microsoft's TrOCR model.

Steps:

1. Collect Urdu images.
2. Preprocess images.
3. Create labels.
4. Build a dataset class.
5. Fine-tune the TrOCR model.
6. Test the model.
7. Deploy using Gradio and Hugging Face Spaces.

---

# Dataset Details

- Total images: 246
- Sources:

  - Books
  - Newspapers
  - Synthetic images
  - Augmented images

- Dataset contains:

  - Printed Urdu
  - Different fonts
  - Different text sizes
  - Different backgrounds

---

# Technologies Used

- Python
- PyTorch
- Transformers
- TrOCR
- Pandas
- Pillow
- Gradio
- Hugging Face

---

# Project Structure

```text
urdu-ocr-codesaviours-si26-usama/

├── data/
│   ├── raw/
│   └── processed/

├── labels.csv
├── README.md
├── app.py
├── requirements.txt

├── week-1.ipynb
├── week-3.ipynb
├── week-4.ipynb
├── week-5.ipynb
```

# Live Demo

Hugging Face Space:

https://huggingface.co/spaces/Usamasarfraz/urdu-ocr-codesaviours-si26-usama-v2

---

# GitHub Repository

https://github.com/Usamasarfrazz/urdu-ocr-codesaviours-si26-Usama

---

# Results

- Dataset size: 246 images
- Training completed successfully.
- The model was trained on Urdu text images.
- Accuracy can be improved with a larger dataset.

---

# How to Run Locally

```bash
git clone https://github.com/Usamasarfrazz/urdu-ocr-codesaviours-si26-Usama.git

cd urdu-ocr-codesaviours-si26-Usama

pip install -r requirements.txt

python app.py
```

---

# Credits

**Usama Sarfraz**

Built during the **Code Saviours ML/AI Internship — Batch SI-26**.
