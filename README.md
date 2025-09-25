# AI-Powered Product Mockup Generator

## 🚀 Overview
This project is a sophisticated AI application that automatically generates realistic product mockups. A user can upload any logo or design, and this tool intelligently removes the background and then uses a state-of-the-art generative model (Stable Diffusion with an IP-Adapter) to blend the design onto a product image described by a text prompt. 

This project demonstrates a practical, end-to-end pipeline combining Computer Vision and advanced Generative AI to solve a real-world business problem in e-commerce and marketing.



## 🛠️ Tech Stack
- **Python**
- **PyTorch**
- **Hugging Face `diffusers`**: For the Stable Diffusion model.
- **IP-Adapter**: For high-fidelity image prompting.
- **`rembg`**: For AI-powered background removal.
- **Pillow (PIL)**: For image processing.
- **Google Colab**: For GPU-accelerated development.

## 🏃 How to Run
1.  Open the `Product_Mockup_Generator.ipynb` file in Google Colab.
2.  Ensure the runtime is set to use a T4 GPU.
3.  Run the consolidated script cell at the top of the notebook.
4.  Follow the prompts to upload your desired logo image.
5.  The final product mockup will be generated and displayed at the end.