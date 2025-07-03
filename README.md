# PRODIGY_GA_04
Image to image translation with CGAN
# Task 04 – Image-to-Image Translation using Conditional GAN (Pix2Pix)

This project demonstrates how to perform image-to-image translation using a Conditional GAN approach. Although the original Pix2Pix model wasn't directly used, a similar result was achieved using the Stable Diffusion Inpainting model available from Hugging Face.

---

## 🎯 Objective

Transform a sketch into a realistic image using a generative AI model by conditioning on an input image and guiding the generation with a text prompt.

---

## 🛠️ Tools and Libraries

- Python (Google Colab)
- Hugging Face Diffusers
- Stable Diffusion Inpainting
- PyTorch
- PIL (Python Imaging Library)

---

## 🔍 Process Overview

1. Installed required libraries: `diffusers`, `torch`, `transformers`, etc.
2. Loaded a sample sketch image from Hugging Face's dataset.
3. Used Stable Diffusion Inpainting as a stand-in for Pix2Pix.
4. Provided a prompt to guide image generation: `"Convert sketch to realistic scenery"`
5. Displayed and saved the generated image.

---

## 💡 Key Outcomes

- Learned the concept of Conditional GANs for image-to-image translation.
- Implemented AI-powered inpainting with Stable Diffusion.
- Practiced prompt-based generative image modeling.
- Gained experience with Hugging Face pipelines for vision-based AI tasks.



