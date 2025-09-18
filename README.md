# Rig Scheduling Optimization with Genetic Algorithm (GA-1 & GA-2)

Genetic Algorithm–based rig scheduling for Workover & Well Services (WO/WS) in mature oilfields.
This repository provides two approaches:
- **GA-1 (non-tiered):** jointly optimizes all wells using production (BOPD) and spatial distance.
- **GA-2 (tiered):** classifies wells by production tiers and applies different optimization rules for each tier.

> **Note:** Original notebooks are formatted for **Google Colab** and preserve the code structure to avoid output changes.

## Features
- Colab-friendly notebooks (`notebooks/GA1_colab.ipynb`, `notebooks/GA2_colab.ipynb`)
- Distance calculations using Haversine
- Convergence and route visualizations
- Sample data schema (no sensitive data included)

## Getting Started (Google Colab)
1. Open Colab → **File > Open notebook** → **GitHub** tab.
2. Paste your repo URL (after you upload this repo) and open `notebooks/GA1_colab.ipynb` or `GA2_colab.ipynb`.
3. Upload your field dataset (if required) to the Colab working directory **or** mount Google Drive and adjust the path in the notebook’s data-loading cell.
4. Run all cells.

## Local Setup (Optional)
```bash
python -m venv .venv
source .venv/bin/activate     # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Repository Structure
```
rig-scheduling-ga/
├─ README.md
├─ LICENSE
├─ requirements.txt
├─ .gitignore
├─ CITATION.cff
├─ CONTRIBUTING.md
├─ CODE_OF_CONDUCT.md
├─ data/
│  ├─ README.md
│  └─ sample_wells.csv          # dummy example (no sensitive data)
└─ notebooks/
   ├─ GA1_colab.ipynb           # original GA-1 code (Colab)
   └─ GA2_colab.ipynb           # original GA-2 code (Colab)
```

## Data Privacy
Do **not** upload internal or confidential datasets. Use `data/sample_wells.csv` as a format reference.
Replace with your own non-sensitive sample if you wish to share examples publicly.

## Citation
If you use this repository, please cite the associated research paper and this software (see `CITATION.cff`).

## License
This project is licensed under the MIT License – see `LICENSE` for details.

## Contributing
Contributions are welcome! Please see `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md`.
