---
title: "AI-Powered Digital Paintings with LoRA"
excerpt: "An AI project using Stable Diffusion 1.5 to create personalized digital paintings for a birthday gift."
collection: portfolio_legacy
layout: single
date: 2023-09-29
tags: [AI, Machine Learning, Stable Diffusion, LoRA, Digital Art]
image: "/images/birthday/generated1.jpg"
---

## Project Overview

For a recent project, I decided to leverage AI to create a unique birthday gift for a friend. The goal was to train a LoRA (Low-Rank Adaptation) model using **Stable Diffusion 1.5** to generate personalized digital paintings that reflect her style and essence.

The challenge was to work with a very limited dataset—about 10 selfies featuring me and my friends. To achieve a consistent character portrayal, which can be quite challenging in AI image generation, I employed various techniques such as model checkpoint selection, prompt engineering, and cherry-picking.

### Key Steps in the Project

1. **Dataset Preparation**: To ensure the AI model focused solely on my friend's likeness, I cropped the photos to include only her face. This step was crucial because, in an initial attempt where I didn't crop the images, the resulting character was a blend of me, her, and other friends, which was not the desired outcome. This refined dataset allowed the model to better generalize from a limited number of photos, capturing her unique features more accurately. For privacy reasons, the original photos are not included on this page.
   
2. **Model Training**: I used **Kohya ss** and **Automatic1111 WebUI** to train the LoRA model, employing a back-and-forth process with multiple training sessions and different settings to progressively improve the output quality. This iterative approach allowed me to refine the model's understanding of the character while experimenting with various configurations. I also performed careful checkpoint selection to strike a balance between maintaining the desired artistic style and accurately capturing the character's likeness. Given the low-quality dataset, the model required a slight degree of overfitting to produce satisfactory results, ensuring the generated images remained true to the intended style and subject.

3. **Prompt Engineering and Cherry-Picking**: Given the constraints, I carefully crafted prompts and cherry-picked the best outputs to ensure the generated images were of high quality and closely matched the desired outcome.

### Challenges and Learnings

Working with a small dataset posed significant challenges. Ensuring that the AI-generated images were both consistent and high-quality required a deep understanding of model behavior and prompt crafting. Additionally, learning the entire process from scratch under a loose deadline (less than a week) was an intense but rewarding experience.

### Final Output

The result was a series of personalized digital paintings that served as a unique and thoughtful birthday gift. Below is a gallery of the AI-generated images created using the trained LoRA model.

---

## AI-Generated Image Gallery

Below is a gallery showcasing a range of AI-generated digital paintings created using the LoRA model trained on Stable Diffusion 1.5. These images demonstrate the versatility and creative potential of the model, capturing various artistic interpretations of the character. While the LoRA model was not specifically fine-tuned for this particular style, it effectively generates compelling results in this context. In theory, the model could be adapted to explore other styles, but I chose to focus on this artistic approach for the final generation.

<div class="gallery">
  <!-- AI Generated Images -->
  <a href="/images/birthday/generated1.jpg">
    <img src="/images/birthday/generated1.jpg" alt="AI Generated Image 1" style="width:100%">
  </a>
  <a href="/images/birthday/generated2.jpg">
    <img src="/images/birthday/generated2.jpg" alt="AI Generated Image 2" style="width:100%">
  </a>
  <a href="/images/birthday/generated3.jpg">
    <img src="/images/birthday/generated3.jpg" alt="AI Generated Image 3" style="width:100%">
  </a>
  <a href="/images/birthday/generated4.jpg">
    <img src="/images/birthday/generated4.jpg" alt="AI Generated Image 4" style="width:100%">
  </a>
  <a href="/images/birthday/generated5.jpg">
    <img src="/images/birthday/generated5.jpg" alt="AI Generated Image 5" style="width:100%">
  </a>
  <a href="/images/birthday/generated6.jpg">
    <img src="/images/birthday/generated6.jpg" alt="AI Generated Image 6" style="width:100%">
  </a>
  <a href="/images/birthday/generated7.jpg">
    <img src="/images/birthday/generated7.jpg" alt="AI Generated Image 7" style="width:100%">
  </a>
  <a href="/images/birthday/generated8.jpg">
    <img src="/images/birthday/generated8.jpg" alt="AI Generated Image 8" style="width:100%">
  </a>
  <a href="/images/birthday/generated9.jpg">
    <img src="/images/birthday/generated9.jpg" alt="AI Generated Image 9" style="width:100%">
  </a>
</div>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.gallery a, .gallery .video-item {
  flex: 1 1 calc(33% - 10px);
  box-sizing: border-box;
  display: block;
  overflow: hidden;
  border-radius: 5px;
  transition: transform 0.3s ease;
}

.gallery a:hover, .gallery .video-item:hover {
  transform: scale(1.05);
}

.gallery img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 5px;
}
</style>

---

### Conclusion

This AI project was a rewarding blend of creativity and technical exploration, providing a unique opportunity to create personalized art through machine learning. It allowed me to tackle the challenge of learning a new skill from scratch while working under a tight deadline. The process was particularly enjoyable and motivating, as the goal was to craft a one-of-a-kind gift for a friend. Despite the constraints of limited resources and time, the project resulted in a collection of digital paintings that serve as both a heartfelt gift and a testament to the creative potential of AI in art.
