# RIDD: Plug-and-Play Interpretable Responsible Text-to-Image Generation | CVPR 2025

![Teaser Image](docs/assets/teaser.png)

[![Paper](https://img.shields.io/badge/Paper-PDF-blue)](docs/papers/RIDD_CVPR2025.pdf)
[![GitHub](https://img.shields.io/badge/Code-GitHub-green)](https://github.com/yourusername/RIDD)
[![Demo](https://img.shields.io/badge/Demo-Video-red)](https://your-demo-url.com)

## 📝 Abstract
Text-to-Image (T2I) diffusion models have raised significant concerns over fairness, bias, and safety.
Existing responsible generation approaches target these issues individually and require modifications to the diffusion model.
We propose **RIDD**, a plug-and-play solution using **concept whitening** and **knowledge distillation** to enable **interpretable and ethical image generation** without altering the original T2I pipeline.

## 📜 Paper
[📄 Read the Paper (PDF)](docs/papers/RIDD_CVPR2025.pdf)

## 🔥 Key Contributions
- **Plug-and-Play:** Works with any T2I model without retraining.
- **Interpretable:** Uses concept whitening for transparency.
- **Multi-Facet Control:** Balances fairness, safety, and bias removal.
- **Scalable:** Works on large-scale diffusion models efficiently.

## 📊 Results
![Results](docs/assets/results.png)

## 💾 Installation
```bash
git clone https://github.com/yourusername/RIDD.git
cd RIDD
pip install -r requirements.txt
