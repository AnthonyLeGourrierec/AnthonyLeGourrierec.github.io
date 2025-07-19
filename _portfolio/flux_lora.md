---
layout: single  # Update with your specific layout name
title: "Training a LoRA on FLUX for Personal Image Generation"
excerpt: "Exploring the potential of FLUX, an open-source model, by training a LoRA with my own photos."
collection: portfolio
lang: en
date: 2024-09-24  # Project completion date
tags: [AI, FLUX, LoRA, StableDiffusion]
technologies: [FLUX, ComfyUI, Civit AI]
role: "AI Experimenter & LoRA Trainer"
image: /images/flux/ComfyUI_00058_.png  # Path to the cover image for the project
hidden: false  # Add this line to hide the project
---

## Overview

FLUX is a new open-source model similar to Stable Diffusion, and I was eager to explore its capabilities. Given my computer's limitations for model training, I decided to use **Civit AI** to train a LoRA model using **25 captioned photos of myself**. This project aimed to evaluate the effectiveness of FLUX in generating both realistic and stylized images of my face by employing two distinct checkpoints with varying levels of training.

**Key Skills Demonstrated:**

- **LoRA Model Training**: Trained a custom LoRA using Civit AI, experimenting with different checkpoints for a tailored results.
- **Model Fine-Tuning**: Selected two different checkpoints, one for realism and one for stylization, balancing likeness with flexibility.
- **ComfyUI Usage**: Set up and ran the FLUX dev model with the LoRA locally on my computer using ComfyUI.

**Technologies Used:** FLUX, ComfyUI, Civit AI

---

## Project Highlights

### Key Features

- **Realistic Likeness with FLUX**: The first LoRA checkpoint was optimized for realistic image generation, focusing on closely replicating my facial features. This was achieved through slightly overfitting the model to prioritize likeness.
- **Stylized Generation**: The second LoRA checkpoint was trained with more flexibility, allowing for creative, stylized outputs that still captured the main features of my face but offered more artistic diversity.
- **Efficient Workflow with Limited Resources**: Despite not having a powerful computer for training, I effectively utilized Civit AI's resources to handle the intensive LoRA training, and then ran the results locally using ComfyUI.

### Achievements

- **Effective Overfitting**: Successfully created a highly realistic version of the LoRA that captured fine details of my face, allowing for accurate representation in image generations.
- **Creative Flexibility**: Developed a more flexible LoRA checkpoint, which enabled artistic and stylized variations of my face while still retaining key identifying features.
- **Resourceful Setup**: Overcame hardware limitations by using external resources for training while running the final model locally.

### Results

The project demonstrated the capabilities of FLUX in both realistic and stylized image generation. By experimenting with overfitting and underfitting, I was able to strike a balance between realism and creativity, with the following outcomes:

- **Increased Likeness**: The overfitted model generated highly realistic images, particularly challenging when creating self-images.
- **Enhanced Creativity**: The stylized checkpoint provided a broader range of artistic interpretations while still retaining the core features of my face.

---

## Visual Gallery

<div class="gallery">
  <a href="/images/flux/ComfyUI_00315_.png"><img src="/images/flux/ComfyUI_00315_.png" alt="Generated Image 11"></a>
  <a href="/images/flux/ComfyUI_00029_.png"><img src="/images/flux/ComfyUI_00029_.png" alt="Generated Image 2"></a>
  <a href="/images/flux/ComfyUI_00038_.png"><img src="/images/flux/ComfyUI_00038_.png" alt="Generated Image 3"></a>
  <a href="/images/flux/ComfyUI_00058_.png"><img src="/images/flux/ComfyUI_00058_.png" alt="Generated Image 4"></a>
  <a href="/images/flux/ComfyUI_00143_.png"><img src="/images/flux/ComfyUI_00143_.png" alt="Generated Image 5"></a>
  <a href="/images/flux/ComfyUI_00162_.png"><img src="/images/flux/ComfyUI_00162_.png" alt="Generated Image 6"></a>
  <a href="/images/flux/ComfyUI_00166_.png"><img src="/images/flux/ComfyUI_00166_.png" alt="Generated Image 7"></a>
  <a href="/images/flux/ComfyUI_00190_.png"><img src="/images/flux/ComfyUI_00190_.png" alt="Generated Image 8"></a>
  <a href="/images/flux/ComfyUI_00341_.png"><img src="/images/flux/ComfyUI_00341_.png" alt="Generated Image 12"></a>
  <a href="/images/flux/ComfyUI_00238.png"><img src="/images/flux/ComfyUI_00238.png" alt="Generated Image 9"></a>
  <a href="/images/flux/ComfyUI_00239_.png"><img src="/images/flux/ComfyUI_00239_.png" alt="Generated Image 10"></a>
  <a href="/images/flux/ComfyUI_00507_.png"><img src="/images/flux/ComfyUI_00507_.png" alt="Generated Image 13"></a>
  <a href="/images/flux/ComfyUI_00533_.png"><img src="/images/flux/ComfyUI_00533_.png" alt="Generated Image 14"></a>
  <a href="/images/flux/ComfyUI_00550_.png"><img src="/images/flux/ComfyUI_00550_.png" alt="Generated Image 15"></a>
  <a href="/images/flux/ComfyUI_00556_.png"><img src="/images/flux/ComfyUI_00556_.png" alt="Generated Image 16"></a>
  <a href="/images/flux/ComfyUI_00573_.png"><img src="/images/flux/ComfyUI_00573_.png" alt="Generated Image 17"></a>
  <a href="/images/flux/ComfyUI_00595_.png"><img src="/images/flux/ComfyUI_00595_.png" alt="Generated Image 18"></a>
  <a href="/images/flux/ComfyUI_00623_.png"><img src="/images/flux/ComfyUI_00623_.png" alt="Generated Image 19"></a>
  <a href="/images/flux/ComfyUI_00643_.png"><img src="/images/flux/ComfyUI_00643_.png" alt="Generated Image 20"></a>
  <a href="/images/flux/ComfyUI_00645_.png"><img src="/images/flux/ComfyUI_00645_.png" alt="Generated Image 21"></a>
  <a href="/images/flux/ComfyUI_00656_.png"><img src="/images/flux/ComfyUI_00656_.png" alt="Generated Image 22"></a>
  <a href="/images/flux/ComfyUI_00663_.png"><img src="/images/flux/ComfyUI_00663_.png" alt="Generated Image 23"></a>
  <a href="/images/flux/ComfyUI_00693_.png"><img src="/images/flux/ComfyUI_00693_.png" alt="Generated Image 24"></a>
  <a href="/images/flux/ComfyUI_00719_.png"><img src="/images/flux/ComfyUI_00719_.png" alt="Generated Image 25"></a>
  <a href="/images/flux/ComfyUI_00724_.png"><img src="/images/flux/ComfyUI_00724_.png" alt="Generated Image 26"></a>
</div>

---

## Closing Thoughts

This project highlights the potential of FLUX as a powerful open-source model for personal image generation. By training a LoRA with 25 captioned photos of myself, I was able to achieve both realistic and creative outputs. The process also demonstrated the effectiveness of leveraging external training resources like Civit AI while managing model execution locally using ComfyUI. This project not only showcased technical skills but also the ability to overcome hardware limitations through resourceful problem-solving.

---

Interested in learning more about this project or collaborating? [Contact me](/contact) or explore [more of my projects](/portfolio/).

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.gallery a {
  flex: 1 1 calc(50% - 10px);  /* Display 2 items per row */
  box-sizing: border-box;
  display: block;
  overflow: hidden;
  border-radius: 5px;
  transition: transform 0.3s ease;
}

.gallery a:first-child {
  flex: 1 1 100%;  /* Make the first image span the entire row */
}

.gallery a:hover {
  transform: scale(1.05);
}

.gallery img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 5px;
}
</style>
