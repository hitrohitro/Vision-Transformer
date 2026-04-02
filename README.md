# Vision Transformer (ViT) Live Demonstration

An interactive, end-to-end Python pipeline demonstrating the capabilities of Vision Transformers (ViTs) for real-time image classification. This repository was built to accompany a live presentation on the architectural advantages of ViTs over traditional CNNs.

## 📌 Project Overview
This project allows a user to input any common noun (e.g., "Golden Retriever", "Sports Car"). The script then dynamically fetches a high-quality, real-world image from the Wikipedia API and classifies it using a pre-trained Vision Transformer from Hugging Face. 

It is designed to be highly robust for live demonstrations, featuring built-in error handling, rate-limit protections, and graceful fallbacks.

## ✨ Features
* **Dynamic Image Sourcing:** Uses the Wikipedia REST API to fetch clean, centered, and high-quality images without requiring API keys.
* **State-of-the-Art ML:** Implements Google's `vit-base-patch16-224` model via the Hugging Face `transformers` library.
* **Production-Ready Code:** Includes robust `try/except` blocks, `io.BytesIO` for safe memory loading, and custom `User-Agent` headers to prevent live-demo server blocks.
* **Companion Presentation:** Includes a comprehensive slide deck explaining ViT architecture, Patch Embeddings, and Transfer Learning.

## 🗂️ Repository Structure
* `vit_live_presentation_demo.ipynb`: The main Jupyter/Colab notebook containing the interactive pipeline.
* `Vision-Transformers-ViTs.pdf`: Presentation slides covering the theory, advantages, and scalability of ViTs.
* `requirements.txt`: List of required Python dependencies.

## 🚀 How to Run

**Option 1: Google Colab (Recommended)**
1. Upload `vit_live_presentation_demo.ipynb` to Google Colab.
2. Run the first cell to install dependencies.
3. Run the main script, type an object into the prompt, and watch the model work!

**Option 2: Local Environment**
1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
   cd your-repo-name