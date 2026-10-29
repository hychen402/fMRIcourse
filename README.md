### fMRI Mini Project
## 🧠 Project Overview
Briefly describe the scientific question or goal of this analysis. 
*Example: "This mini-project analyzes the neural correlates of working memory using a block-design fMRI task. The analysis pipeline is built in MATLAB using SPM12."*

## 🛠️ Software Requirements
List the exact software versions required to run the code smoothly:
* MATLAB (e.g., R2023b or newer)
* [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) (Version 7771)

## 📁 Repository Structure
This repository contains **only** the analysis code. No raw neuroimaging data or generated derivatives are hosted here.
```text
fMRI_MiniProject/
├── .gitignore               <-- Prevents temporary MATLAB files from uploading
├── README.md                
└── scripts/                 <-- Analysis pipeline
    ├── 01_preprocessing.m
    ├── 02_first_level.m
    └── 03_group_level.m

