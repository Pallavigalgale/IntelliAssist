# IntelliAssist 🚀
**Generative AI-based IT Service Desk Assistant**  
*Version 2.0: Fine-tuned T5 model for automatic ticket categorization and resolution.*

---

## 🔹 Project Overview
IntelliAssist is an AI-powered assistant designed to automate IT support ticket handling.  
It uses a **fine-tuned T5 transformer model** to predict the **category** of incoming tickets and generate **draft resolutions** based on historical ticket data.

---

## 🔹 Features
- **Automatic Ticket Categorization:** Password Reset, Network Issue, Hardware Issue, Software Installation, Account Lockout, etc.  
- **Draft Resolution Generation:** Provides preliminary solutions for IT support tickets.  
- **Fine-Tuned T5 Model:** Tailored to IT service desk domain using historical ticket data.  
- **GPU Acceleration:** Supports CUDA for faster training and inference.  
- **Robust Parsing:** Regex-based extraction ensures accurate category and resolution detection.

---

## 🔹 Installation
This project is optimized for **Google Colab**:

```bash
!pip install transformers datasets accelerate --quiet
