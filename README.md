# Graduation Project: Fine-Tuning MedGemma for Medical Image Classification and Captioning

## Overview
This project focuses on fine-tuning **MedGemma**, a state-of-the-art multimodal vision-language model, to perform medical image classification and text generation tasks. The project aims to help in automated medical diagnosis by enhancing the accuracy and performance of MedGemma on specific medical datasets.

---

## Features
- Classification of colorectal tissue images (NCT-CRC-HE-100K dataset)
- Caption generation for chest X-rays (RSNA dataset)
- User-friendly API to provide text-based reports from uploaded medical images
- Training performed on Google Colab using PEFT (Parameter-Efficient Fine-Tuning) techniques

---

## Technologies Used
- **Model:** MedGemma built on Gemma3 architecture
- **Datasets:**
  - NCT-CRC-HE-100K (colon tissue)
  - RSNA pneumonia dataset (chest X-rays)
- **Frameworks:** Hugging Face Transformers, PyTorch
- **Tools:** Google Colab, GitHub
- **APIs:** Custom Flask API for demo

---

## My Role
- Participated in dataset preparation and data labeling
- Assisted in adapting the fine-tuning scripts on Colab
- Helped build the API deployment demo
- Presented the project with the team

---

## Demo
👉 [API Demo](https://drive.google.com/file/d/11RLpDMZ2eM_Pc2Eswu3cLTAYNy-8WXvk/view?usp=drivesdk)

---

## Colab Notebooks
- [Colon tissue fine-tuning notebook](https://colab.research.google.com/drive/1rOQrAkFkhguH85kuI9pUfV8GwFj3b1D-?usp=sharing)  
- [RSNA pneumonia fine-tuning notebook](https://colab.research.google.com/drive/1JCBHMRdaPEDoDuV1hq1hK-MveW3yuxz-?usp=sharing)

---
License
Open source for educational purposes.
-------

## Installation

```bash
git clone https://github.com/abeertawab/medgemma-finetuning.git
