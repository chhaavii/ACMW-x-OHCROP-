# 🤖 ACM-W × OH CROP Design Club — Generative AI Challenge

**Submitted by:** Chhavi · `2024A7PS0193U`  
**Deadline:** 7 April 2026  
**Competition:** ACM-W Chapter × OH CROP Design Club — Generative AI Challenge

---

## 📁 Repository Structure

```
ACMW-x-OHCROP-/
│
├── Challenge1_Image_Repair_Style_Transform.ipynb   # Challenge 1 notebook
├── Challenge1.png                                   # Challenge 1 visual output
│
├── Challenge2_AI_Fashion_Designer.ipynb             # Challenge 2 notebook
├── challeneg2.png                                   # Challenge 2 visual output
│
├── Challenge3_AI_Poster_Designer (1).ipynb          # Challenge 3 notebook
├── ron_weasley_poster_concept_1.svg                 # Poster concept A
├── ron_weasley_poster_concept_2.svg                 # Poster concept B
└── ron_weasley_final_poster.svg                     # Final poster (standalone)
```

---

## 🏆 Challenges Overview

### Challenge 1 — Image Repair + Style Transformation
**Type:** Core Technical | **Points:** 15

An image degradation and reconstruction pipeline using generative techniques. A clean input image is intentionally corrupted, then repaired using a generative model (autoencoder / VAE), and finally transformed into a new visual style while preserving its original structure.

**What was done:**
- Selected a base image dataset
- Applied a degradation method (blur / noise / corruption)
- Used a generative model to reconstruct the degraded image
- Applied style transformation to the repaired output

**Deliverables:** `Challenge1_Image_Repair_Style_Transform.ipynb` · `Challenge1.png`

---

### Challenge 2 — AI Fashion Designer
**Type:** Technical Creative | **Points:** 20

A generative model trained on a fashion dataset to produce a coherent, themed fashion collection. Latent space exploration through sampling and interpolation was used to generate visually consistent outfit designs.

**What was done:**
- Defined a clear fashion theme
- Trained a generative model on a fashion dataset
- Explored the latent space via sampling and interpolation
- Generated 3–5 visually consistent outfit designs

**Deliverables:** `Challenge2_AI_Fashion_Designer.ipynb` · `challeneg2.png`

---

### Challenge 3 — AI Poster Designer
**Type:** Core Creative | **Points:** 20

A satirical retro-vintage poster series featuring **Ron Weasley** from the Harry Potter universe — playing on internet meme culture around the character (the chess sacrifice, Scabbers being a war criminal, spider phobia, and his perpetually underrated heroism). Three initial concepts were generated and refined into a final cohesive poster.

**Concept & Mood:** Retro / Vintage — aged parchment textures, 1940s propaganda-poster typography, Ministry of Magic bureaucratic aesthetic, Gryffindor red and gold palette.

**The three concepts:**
| File | Concept |
|------|---------|
| `ron_weasley_poster_concept_1.svg` | "Wanted: A Weasley" — Classic propaganda recruitment poster |
| `ron_weasley_poster_concept_2.svg` | "The Classified Dossier" — Art deco Ministry of Magic spy file |
| `ron_weasley_final_poster.svg` | "Not the Chosen One" — Grand portrait poster **(FINAL)** |

**What was done:**
- Defined concept and mood (satirical retro / vintage)
- Generated initial visual ideas using AI
- Refined outputs into a final cohesive poster
- Exported final poster as a standalone `.svg` file

**Deliverables:** `Challenge3_AI_Poster_Designer (1).ipynb` · `ron_weasley_poster_concept_1.svg` · `ron_weasley_poster_concept_2.svg` · `ron_weasley_final_poster.svg`

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Jupyter Notebook (`.ipynb`) | Implementation & documentation |
| PyTorch / TensorFlow | Generative model training |
| Pillow (PIL) | Image processing & style effects |
| Matplotlib | Visualization & layout composition |
| NumPy | Numerical operations & noise generation |
| Stable Diffusion / VAE / Autoencoder | Generative image models |
| SVG | Final poster format (Challenge 3) |

---

## ▶️ How to Run

All notebooks are designed to run on **Google Colab** with GPU enabled.

1. Open the desired `.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Go to **Runtime → Change runtime type → GPU** (T4 recommended)
3. Run all cells top to bottom (`Runtime → Run all`)
4. All outputs are pre-executed and visible without re-running

> Note: Challenge 1 and 2 notebooks may download model weights on first run. Challenge 3 uses SVG-based output with no external model downloads required.

---

## 📊 Evaluation Criteria

As per the competition brief, submissions are evaluated on:

- Clarity of workflow
- Quality of outputs
- Creativity and originality
- Evidence of experimentation and iteration

---

## 📬 Submission Notes

- All notebooks are fully executed with visible outputs
- All links are publicly accessible
- Final poster for Challenge 3 is provided as a standalone file (`ron_weasley_final_poster.svg`)
- Each notebook includes an explanation of approach, methodology, tools used, and key design decisions

---

*Submitted for the ACM-W × OH CROP Design Club Generative AI Challenge · April 2026*
