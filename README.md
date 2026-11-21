<div align="center">

# 🌀 Chaos Game Representation of DNA & Protein Sequences

**A Flask web app that turns DNA and protein sequences into fractal Chaos Game Representation (CGR) images, so motifs and composition show up as patterns.**

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask)
![Biopython](https://img.shields.io/badge/Biopython-FASTA-yellowgreen)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)

</div>

---

## 📌 What is CGR?

Chaos Game Representation maps a sequence onto a polygon. Start at the centre, and for each residue move **halfway toward the vertex** assigned to it. The resulting point cloud is a fractal "fingerprint" of the sequence: k-mer frequencies, repeats and compositional bias become visible.

| Sequence | Polygon | Vertex mapping |
|---|---|---|
| 🧬 DNA | Square | A (0,0) · C (1,0) · G (1,1) · T (0,1) |
| 🧪 Protein | Dodecagon (12 vertices) | Amino acids grouped by physicochemical property: `ILVM`, `RK`, `DE`, `N`, `Q`, `H`, `ST`, `P`, `AG`, `C`, `FY`, `W` |

## ✨ Features

- Upload any **FASTA** file (parsed with Biopython)
- Generate a **DNA CGR** or a **protein CGR**
- Sample genomes and proteins included: African elephant, Bengal tiger, giraffe, green sea turtle, zebrafish, *E. coli*
- Project report: `IBS_A9_Report.pdf`

## 🖼️ Screenshots

![Flask Web Page](https://github.com/user-attachments/assets/f606cf8e-37d3-401e-8c39-c90199f1836d "Flask Web Page")

| CGR of DNA | CGR of Protein |
|---|---|
| ![CGR of DNA](https://github.com/user-attachments/assets/cdb66b1a-adab-4753-a5d8-bac5f4eec5ba) | ![CGR of Proteins](https://github.com/user-attachments/assets/30820adf-e4e7-4d11-9135-535de47ae3f4) |

## 🚀 Run

```bash
pip install flask biopython matplotlib numpy
python app.py
# open http://127.0.0.1:5000 and upload a file from static/uploads/
```

## 👩‍💻 Author

**Ghanasree S**: [GitHub](https://github.com/Ghanasree-S) · [LinkedIn](https://www.linkedin.com/in/ghanasree-s-88976b2b0)
