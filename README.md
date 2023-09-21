# Drought Scope
This repository contains the code for the submission to the [IMAGIN-e challenge](https://github.com/AI4EO/orbitalAI/tree/main/IMAGIN-e) 

## Set the environment
1. Install [Poetry](https://python-poetry.org/)
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

2. Download repo from GitHub
```bash
git clone https://github.com/latitudo40organization/drought-scope
```

3. Install dependencies
```bash
poetry lock && poetry install
```

## Repository content
- [drought_scope.pth](drought_scope.pth): PyTorch model weight 
- [Solution.ipynb](Solution.ipynb): Jupyter notebook

## Dataset
Download the dataset from zenodo and unzip data in /data/ folder
```
https://zenodo.org/record/8363750
```

## Meet the team
The team is composed of researchers from both academia and industry. This project is a collaboration between Latitudo 40, University of Naples Federico II and University of Genova.

- **Antonio Elia Pascarella (1)**
- **Mattia Rigiroli (2)(3)** 
- **Giovanni Giacco (1)(2)**
- **Donato Amitrano (2)(4)**
- **Paolo De Piano (2)**

(1) University of Naples Federico II, Department of Electrical Engineering and Information Technology, Via Claudio 21, 80125 Naples, Italy \
(2) Latitudo 40 srl, Via Emanuele Gianturco 31C, 80142 Naples, Italy \
(3) University of Genova, Department of Civil, Chemical and Environmental Engineering, Via Montallegro 1, 16145 Genova, Italy \
(4) Italian Aerospace Research Centre, Via Maiorise snc, 81043 Capua, Italy