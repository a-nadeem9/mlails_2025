# Metabolite Analysis Pipeline

A workflow for metabolomics data.

---

## Quick Start
1. **Clone:**
   ```bash
   git clone https://git.imp.fu-berlin.de/adin00/mlails-2025.git
   cd source
   ```

2. **Env setup:**
    - Windows (Powershell):
        ```powershell
        python -m venv .venv
        .\.venv\Scripts\Activate.ps1
        pip install --upgrade pip
        pip install -r requirements.txt
        ```

    - macOS/Linux:
        ```bash
        python3 -m venv .venv
        source .venv/bin/activate
        pip install --upgrade pip
        pip install -r requirements.txt
        ```

3. **Run:**
    ```bash
    jupyter lab 02_classification_analysis.ipynb
    ```

