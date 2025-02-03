# 🖼️ Stable Diffusion Image Generation in Google Colab  

This project demonstrates how to use **Stable Diffusion (runwayml/stable-diffusion-v1-5)** for **text-to-image generation** in **Google Colab**.  

## 🚀 Features  
- Generate high-quality images from text prompts  
- Runs efficiently on Google Colab with GPU acceleration  
- Uses **Hugging Face Diffusers** for model loading and inference  
- Supports **custom prompts** to create unique AI-generated images  

## 📦 Requirements  
Before running the notebook, ensure you have:  
- **Google Colab** with GPU enabled  
- **Python 3.7+**  
- Installed dependencies (see below)  

## 🔧 Installation & Setup  
1. Open Google Colab and **enable GPU**:  
   - Go to **Runtime** → **Change runtime type** → **Select GPU**  
2. Install the required libraries:  
   ```bash
   !pip install torch torchvision transformers diffusers accelerate
   Load the Stable Diffusion model:
Initialize the model:
Use Stable Diffusion v1.5 from Hugging Face (runwayml/stable-diffusion-v1-5), and load it into the pipeline with GPU support.

Set up the pipeline:
Move the model to GPU using pipe.to("cuda") for better performance.

Generate an image:
Provide a text prompt (e.g., "A vibrant yellow cockatiel...") to generate the image.

Save and display:
Save the generated image as "cockatiel.png" and display it.

   
