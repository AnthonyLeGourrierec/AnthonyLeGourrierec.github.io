---
layout: single  # Update with your specific layout name
title: "Entraînement d'une LoRA sur FLUX pour la génération d'images personnelles"
excerpt: "Expérimentation du modèle open source FLUX en l'entraînant sur mes propres photos."
collection: portfolio
permalink: /fr/portfolio/flux_lora/
lang: fr
date: 2024-09-24  # Project completion date
tags: [AI, FLUX, LoRA, StableDiffusion]
technologies: [FLUX, ComfyUI, Civit AI]
role: "AI Experimenter & LoRA Trainer"
image: /images/flux/ComfyUI_00058_.png  # Path to the cover image for the project
hidden: false  # Add this line to hide the project
---

## Aperçu

FLUX est un nouveau modèle open source proche de Stable Diffusion que j'étais impatient de tester. Ne disposant pas d'un PC assez puissant pour l'entraînement, j'ai utilisé **Civit AI** afin de créer une LoRA à partir de **25 photos légendées de moi-même**. L'objectif était d'évaluer FLUX pour produire des images réalistes ou stylisées de mon visage via deux checkpoints différents.

**Compétences mises en avant :**

- **Entraînement de LoRA** : création d'un modèle personnalisé via Civit AI et tests de plusieurs checkpoints ;
- **Ajustements du modèle** : choix de deux checkpoints, l'un réaliste et l'autre plus stylisé ;
- **Utilisation de ComfyUI** : exécution locale du modèle FLUX couplé à la LoRA.

**Technologies utilisées :** FLUX, ComfyUI, Civit AI

## Points forts du projet

### Principales caractéristiques

- **Ressemblance réaliste** : premier checkpoint dédié à la reproduction fidèle de mon visage, légèrement surappris pour privilégier la ressemblance ;
- **Génération stylisée** : second checkpoint plus flexible pour des rendus créatifs ;
- **Workflow efficace malgré peu de ressources** : entraînement sur Civit AI puis exécution locale via ComfyUI.

### Réalisations

- **Surapprentissage maîtrisé** : obtention d'un modèle très réaliste reproduisant fidèlement les détails de mon visage ;
- **Variété de rendus stylisés** : production d'images créatives montrant la polyvalence de FLUX ;
- **Usage ingénieux des ressources** : appui sur Civit AI pour pallier le manque de puissance locale.

### Résultats

Le projet a permis de créer des images fidèles comme des rendus plus artistiques tout en tirant parti d'un entraînement externe. La LoRA s'est révélée performante sur les deux checkpoints, montrant le potentiel de FLUX pour la génération d'images personnelles.

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

## Conclusion

Ce projet met en lumière le potentiel de FLUX pour la génération d'images personnelles. En entraînant une LoRA sur 25 photos légendées, j'ai obtenu des rendus à la fois réalistes et créatifs. L'utilisation de ressources externes comme Civit AI, combinée à une exécution locale via ComfyUI, prouve qu'il est possible de contourner les limites matérielles.

---

Pour en savoir plus ou envisager une collaboration, [contactez-moi](/fr/contact) ou découvrez [mes autres projets](/fr/portfolio/).
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
