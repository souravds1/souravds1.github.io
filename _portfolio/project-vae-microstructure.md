---
title: "Machine Learning for 2D Microstructure Generation"
excerpt: "Developed a two-stage VAE and Latent Diffusion Model (LDM) pipeline in PyTorch for high-fidelity synthetic microstructure generation."
collection: portfolio
category: course-projects
---

This project from my Machine Learning & Data Analytics course explores the use of deep generative models to synthesize realistic 2D microstructure images, a critical step for computational materials design.

[View Project Folder on GitHub](https://github.com/souravds1/Portfolio/tree/96b6bc3bc701147c080c883765eb9cec870c2dac/Machine%20Learning%20and%20Data%20analytics){: .btn .btn--research}

[Download Full Report (PDF)](https://github.com/souravds1/souravds1.github.io/blob/a5303f498cbc4cf6c9beedfef0593a34627db9dd/files/Project_Exploring_Variational_Autoencoders_for_2D_Microstructure.pdf){: .btn .btn--research}

---

### Two-Stage Generative Pipeline

To generate high-quality synthetic microstructures, a two-stage pipeline was developed:

1.  **Denoising Variational Autoencoder (VAE):** A custom data-loading pipeline was built in **PyTorch** to create paired clean/noisy image examples. The VAE was trained to learn robust latent representations from data perturbed with three distinct noise models: salt-and-pepper flips, sinusoidal grid overlays, and frequency-domain masking using Fast Fourier Transform (FFT).

2.  **Latent Diffusion Model (LDM):** A diffusion model was trained in the VAE’s learned latent space. This process iteratively refines the latent vectors, significantly improving the fidelity and quality of the final generated microstructure images compared to using a standalone VAE.

### Key Skills & Technologies Demonstrated
* **Generative Models:** Variational Autoencoders (VAEs), Latent Diffusion Models (LDMs)
* **Framework & Libraries:** **PyTorch**
* **Techniques:** Denoising Autoencoders, Latent Space Diffusion, Fast Fourier Transform (FFT) for Data Augmentation, Custom Data-Loading Pipelines.
