# Stats & Probability 101

This repository is a starter kit for your first course using **JupyterLab** with Python.

## Structure
- `assignments/` → Notebooks you submit (start here).
- `data/` → Small datasets for exercises.
- `utils/` → (Optional) Python helpers you write later.
- `environment.yml` → Conda environment spec you can use for class.
- `requirements.txt` → Pip alternative to install dependencies.
- `.gitignore` → Keeps large/temporary files out of Git history.

## Quick Start
1. Create and activate the conda env:
   ```bash
   conda env create -f environment.yml
   conda activate stats-prob-101
   ```
   Or with pip:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

2. Launch JupyterLab:
   ```bash
   jupyter lab
   ```

3. Open `assignments/assignment00_intro.ipynb` and run all cells.

## Git/GitHub (from JupyterLab Terminal)
Initialize the repo and push to GitHub (replace `YOUR-USERNAME`):
```bash
git init
git add .
git commit -m "Initial commit: course starter"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/stats-probability-101.git
git push -u origin main
```

> Tip: Before committing, use **Kernel → Restart Kernel and Run All** so outputs match your code.
