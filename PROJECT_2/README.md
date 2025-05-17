# Assessing the Impact of Data Corruption and Cleaning on Metabolomics Classification

This project analyzes how missing and corrupted data affect the performance of machine learning classifiers (SVM and Neural Networks) on metabolomics data. It also evaluates how different cleaning strategies influence model results and feature importance.

---

## Project Overview

We used the MTBLS92 metabolomics dataset and generated 11 versions of it by:
- Introducing missing values and corrupted values (10% and 50%)
- Applying different cleaning strategies: mean imputation, KNN imputation, and row deletion

We evaluated the impact on classification performance (Accuracy, AUC) and on the stability of selected features.

---

## Quick Start

Open your favorite code editor and follow the steps: 

1. **Clone**
   ```bash
   git clone https://git.imp.fu-berlin.de/adin00/mlails-2025.git
   cd mlails-2025\PROJECT_2
   ```

2. **Env setup**
    - Windows (Powershell)
        ```powershell
        python -m venv .venv
        .\.venv\Scripts\Activate.ps1
        .venv\Scripts\python.exe -m pip install --upgrade pip
        pip install -r requirements.txt
        ```

    - macOS/Linux
        ```bash
        python3 -m venv .venv
        source .venv/bin/activate
        .venv/bin/python.exe -m pip install --upgrade pip
        pip install -r requirements.txt
        ```

3. **Run**
    ```bash
    jupyter lab
    ```

