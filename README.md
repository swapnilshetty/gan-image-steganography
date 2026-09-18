# Secure Image Steganography with GAN Architecture

### A High-Fidelity and Robust Data Hiding Approach

This repository contains my published research work on a GAN-based
image steganography framework for secure and imperceptible data hiding.

## 📄 Publication

**Title:**  
Secure Image Steganography with GAN Architecture: A High-Fidelity and Robust Data Hiding Approach

**Authors:**  
Swapnil Shetty, Puneeth R P

**Published in:**  
2025 9th International Conference on Electronics, Communication and Aerospace Technology (ICECA)

**Publisher:**  
IEEE

**Conference Location:**  
Coimbatore, India

**Conference Dates:**  
05–07 November 2025

**Publication Year:**  
2025

**DOI:**  
10.1109/ICECA66444.2025.11383271

**IEEE Xplore:**  
[View Publication on IEEE Xplore](https://doi.org/10.1109/ICECA66444.2025.11383271)

## 🎤 Conference Presentation

The research paper was presented at ICECA 2025.

The presentation was held at RVS Technical Campus, Coimbatore,
India, during the 9th International Conference on Electronics,
Communication and Aerospace Technology.

## 🔬 Research Overview

This research proposes a GAN-based image steganography architecture
consisting of three primary components:

- **Generator** — embeds the secret message into the cover image.
- **Discriminator** — distinguishes between cover and generated stego images.
- **Extractor** — recovers the hidden binary message from the stego image.

The framework embeds fixed-length **128-bit binary messages** into
images and combines adversarial and extraction losses to balance
visual imperceptibility and message recovery.

## 🧠 Methodology

The proposed architecture follows three major stages:

1. A 128-bit binary message is transformed into a spatial representation.
2. The message representation is combined with the cover image and
   processed by the Generator to produce a stego image.
3. The Discriminator and Extractor support adversarial training and
   accurate message recovery.

## 📊 Experimental Results

Experiments were conducted using the **Set14 dataset** as a
proof-of-concept evaluation.

| Metric | Proposed Method |
|---|---:|
| PSNR | **39.10 dB** |
| SSIM | **0.97** |
| Bit Accuracy Rate (BAR) | **96.80%** |
| Payload | **128 bits** |
| Image Resolution | **64 × 64** |
| Dataset | **Set14** |

### Comparison with Baseline Methods

| Method | PSNR (dB) | SSIM | BAR (%) |
|---|---:|---:|---:|
| LSB | 30.50 | 0.92 | 75.00 |
| SteganoGAN | 36.80 | 0.95 | 94.50 |
| **Proposed Method** | **39.10** | **0.97** | **96.80** |

## 🔑 Research Areas

- Image Steganography
- Generative Adversarial Networks (GANs)
- Deep Learning
- Computer Vision
- Data Hiding
- Secure Image Communication

## 📌 Key Contributions

- GAN-based embedding of binary messages into cover images.
- Adversarial training for improved stego-image imperceptibility.
- An extractor network for hidden-message recovery.
- Combined adversarial and extraction objectives for training.
- Evaluation using PSNR, SSIM, and Bit Accuracy Rate.

## ⚠️ Scope and Limitations

The experiments were conducted as a proof-of-concept using the
Set14 dataset, which contains 14 natural images.

The current framework supports a fixed **128-bit payload** and
uses **64 × 64 pixel** images.

The reported evaluation did not test robustness against:

- JPEG compression
- Noise addition
- Geometric modifications
- Sophisticated steganalysis attacks

Larger and more diverse datasets, adaptive embedding, higher
resolution inputs, and robustness evaluation are identified as
areas for future research.

## 📄 Full Paper

The manuscript is available in the [`paper/`](paper/) directory.

**[Read the Full Paper](paper/secure-image-steganography-paper.pdf)**

**[View the Published Paper on IEEE Xplore](https://doi.org/10.1109/ICECA66444.2025.11383271)**

## 🏆 Presentation Certificate

The repository also contains the certificate confirming presentation
of this research paper at ICECA 2025.

**[View Presentation Certificate](paper/certificate-of-presentation.pdf)**

## 👤 Author

**Swapnil Shetty**

M.Tech – Computer Science and Engineering  
NMAM Institute of Technology, Nitte
