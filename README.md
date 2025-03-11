# RIDD: Plug-and-Play Interpretable Responsible Text-to-Image Generation

RIDD introduces a novel **plug-and-play** framework for interpretable and responsible text-to-image (T2I) generation. Our approach **enables fine-grained control over generated images** by dynamically adjusting attributes such as **age, gender, and race** while maintaining fidelity and fairness in AI-generated content.

![Teaser Image](./static/images/cvpr_general_2-03.png)

## **Table of Contents**
- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [BibTeX](#bibtex)
- [Contributors](#contributors)
- [License](#license)

---

## **Introduction**
The rapid advancement in **diffusion models** has enabled high-quality text-to-image synthesis. However, **interpretability, fairness, and responsible generation** remain key challenges. **RIDD** addresses these challenges by:
- Providing **fine-grained control** over attributes like **age, gender, and race**.
- Using **knowledge distillation** and **concept whitening** for interpretable changes.
- Ensuring **responsible AI** by mitigating biases in generated images.

---

## **Features**
✅ **Plug-and-play concept control** - Users can modify age, gender, and race dynamically.  
✅ **Dual-space multi-facet control** - Combines concept whitening and knowledge distillation.  
✅ **Intuitive UI** - Uses a **slider-based control** to progressively modify generated images.  
✅ **Fair and responsible AI** - Prevents unintended biases in diffusion-based models.  
✅ **ArXiv Paper, Code, and Interactive Demo** available for deeper exploration.

---

## **Demo**
🔗 **Live Demo**: [Coming Soon](#)  
🔗 **Project Page**: [View Here]([Plug and Play Control](https://basim-azam.github.io/))  

---

## **Installation**
To run RIDD locally, follow these steps:

### Clone the Repository
```sh
git clone https://github.com/yourusername/RIDD.git
cd RIDD
```

### Intsall Dependencies
```sh
pip install -r requirements.txt
```

### BibTex
If you use RIDD in your research , please Cite: 

@inproceedings{azam2025ridd,
  author    = {Basim Azam and Naveed Akhtar},
  title     = {Plug-and-Play Interpretable Responsible Text-to-Image Generation via Dual-Space Multi-facet Concept Control},
  booktitle = {CVPR},
  year      = {2025},
}

### Acknowledments
We acknowledge contributions from
- The University of Melbourne
- OpenAI and Stable Diffusion
- Github Repos ()

