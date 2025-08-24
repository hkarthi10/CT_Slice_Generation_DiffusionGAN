# CT_Slice_Generation_DiffusionGAN  
**Diffusion-GAN for Abdominal CT Slice Synthesis**

This project implements a **basic Diffusion-GAN pipeline** using a U-Net-based architecture, focused on exploring **generative diffusion techniques** for medical imaging.  
Although the model does not yet generate complete CT slices, it successfully learns **noise prediction** and demonstrates **progressive image quality improvement** through diffusion-based denoising.

---

## 🧠 Objective  
- Understand and implement a **Diffusion-GAN** pipeline.  
- Experiment with **diffusion-based noise scheduling**.  
- Train a model to **predict noise** and improve image quality.  

---

## 📁 Repository Contents  
- **`Diffusion_GAN_for_Abdominal_CT_Synthesis.ipynb`** – Main notebook containing training loop, diffusion pipeline, and visualization.  
- **`forward-diffusion-scheduler.ipynb`** – Notebook handling the forward noise schedule.  

---

## 🏗️ Architecture  
- **Generator:** U-Net style encoder–decoder.  
- **Diffusion Process:** Forward noise addition and reverse denoising steps.  
- **Loss Function:** Mean Squared Error (MSE) between predicted and true noise.  

---

## 📊 Results  
- The model was trained on **dummy abdominal CT slices**.  
- While it does **not yet generate full synthetic slices**, it can:  
  - Accurately **predict noise patterns**.  
  - Show **progressive image quality improvements** over diffusion steps.  

*(Sample output images are included in the repository under the `outputs/` folder.)*  

---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/hkarthi10/CT_Slice_Generation_DiffusionGAN.git
   cd CT_Slice_Generation_DiffusionGAN
