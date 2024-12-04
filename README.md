# General LaTeX Projects Repository

This repository contains various LaTeX projects that I am consolidating from Overleaf. Over time, it will house my smaller projects for easier management and version control. 

---

## Current Structure

### 📂 `PHY661 PETMRVSCT`
This folder contains the most recent work on a radiotherapy paper comparing **PET/CT** and **PET/MR** modalities. The project includes the following key files:

#### **Key Files:**
- **`main.tex`**: The primary LaTeX file for the paper.
- **`references.bib`**: Bibliography file containing references for the paper.
- **`main.pdf`**: The compiled PDF of the paper.

#### **Figures:**
All figures for this project are stored in the `assets` subdirectory:
- `GTV_Delineation_PETCT_vs_PETMRI.png`: Comparison of GTV delineation using PET/CT and PET/MRI.
- `PETMRI_vs_Conventional_Workflow.png`: PET/MRI workflow vs. conventional methods.
- `Liver_Dosimetry_Differences.png`: Differences in liver dosimetry between PET modalities.
- `Respiratory_Motion_Artifacts.png`: Artifacts due to respiratory motion.
- `PETCT_vs_PETMRI_Phantom.png`: Phantom study comparison for PET/CT and PET/MRI.

---

## Future Plans
1. Migrate all existing projects from Overleaf into this repository.
2. Organize each project into its own folder with:
   - `main.tex`: The main LaTeX document.
   - `references.bib`: Bibliography file.
   - `assets/`: A folder for figures, tables, or any supplementary material.
3. Maintain a clear structure for easy navigation and collaboration.

---

## Repository Map

```
LaTex--projects/
│
├── PHY661 PETMRVSCT/
│   ├── assets/
│   │   ├── GTV_Delineation_PETCT_vs_PETMRI.png
│   │   ├── PETMRI_vs_Conventional_Workflow.png
│   │   ├── Liver_Dosimetry_Differences.png
│   │   ├── Respiratory_Motion_Artifacts.png
│   │   └── PETCT_vs_PETMRI_Phantom.png
│   ├── main.tex
│   ├── references.bib
│   ├── main.pdf
│   └── (auxiliary files: *.aux, *.log, etc.)
│
└── (More projects to be added)
```

---

## How to Use
1. Navigate to a project directory (e.g., `PHY661 PETMRVSCT`).
2. Open `main.tex` in your preferred LaTeX editor.
3. Compile the document using `pdflatex`, `xelatex`, or your LaTeX editor's build system.
4. Figures are stored in the `assets/` directory and referenced in the LaTeX file.

---

## License
This repository is private and intended for academic use only. Any use or distribution of the contents must be approved by the repository owner.
