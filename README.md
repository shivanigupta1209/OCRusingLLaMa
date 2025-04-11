# OCR + LLaMA Inference Project

This project performs OCR (Optical Character Recognition) on images and leverages a LLaMA-based language model to process and understand the extracted text. It is built using Hugging Face Transformers and supports quantized inference for efficiency.

## 📦 Features

- OCR on images using OpenCV and PIL.
- Integration with Hugging Face's LLaMA models.
- Efficient inference using `bitsandbytes` and `accelerate`.
- Handles large models via `accelerate` and device map loading.

## 🛠️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/ocr-llama-project.git
cd ocr-llama-project
pip install -r requirements.txt
