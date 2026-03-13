A PyTorch implementation of the DDPM paper with detailed notes & derivations.

This repository contains an implementation of "Denoising Diffusion Probabilistic Models" (Ho et al., 2020) along with comprehensive mathematical explanations and training scripts.

📌 Overview Diffusion models are a class of generative models that learn to generate data by gradually denoising a normally distributed variable. This repo includes:

✅ PyTorch implementation of DDPM (training & sampling).

📝 Detailed notes on the theory and derivations (Markdown/PDF).

🖼️ Demo scripts for image generation (e.g., MNIST/CIFAR-10).

🔥 Key Features ✔ Forward & Reverse Process – Gaussian noise diffusion and learned denoising. ✔ U-Net Model – Noise prediction using a time-conditioned U-Net. ✔ Flexible Training – Works on custom datasets (images, audio, etc.). ✔ Mathematical Breakdown – Step-by-step derivations of the loss function and sampling process.
