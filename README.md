# Midterm Project - Pairs Trading

An archive of deliverables and progress for the Fintech & Quant Trading project.

### 1. Clone the repository

```bash
git clone https://github.com/riodino14/FintechGroupProject.git
cd FintechGroupProject
```

### 2. Set up uv

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) once:

macOS / Linux:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Windows (PowerShell):

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Restart your terminal, then run from the project folder:

```bash
uv sync
```

### 3. Open in VS Code (optional)

```bash
code --install-extension ms-python.python
code --install-extension ms-toolsai.jupyter
code .
```

### 4. Run the notebook

In VS Code: open a notebook in `0_notebooks/` → **Select Kernel** → `.venv` → **Run All**.

Or use JupyterLab in your browser:

```bash
uv run python -m ipykernel install --user --name fintech-group --display-name "Fintech Group"
uv run --with jupyterlab jupyter lab
```

Open the notebook → select the **Fintech Group** kernel → **Run All**.

### Get updates

```bash
git pull
uv sync
```

### Add a dependency

```bash
uv add <package-name>
```
