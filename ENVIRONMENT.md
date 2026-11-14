# Project environment

Use Python 3.13 for the same Python version used to validate this project.
Run these commands from the repository root:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

On Windows, activate with `.venv\Scripts\activate` instead.

## Run the notebooks

```bash
python -m jupyterlab
```

Open `notebooks/online_shoppers_data_preparation.ipynb` and run the cells in order.
In VS Code, select `.venv/bin/python` (Windows: `.venv\Scripts\python.exe`)
as the notebook kernel. If needed, register a named kernel:

```bash
python -m ipykernel install --user --name aai501 --display-name "AAI-501 Project"
```

The notebook uses the local dataset if present and fetches it through `ucimlrepo`
otherwise. Fetching requires internet access. Set `USE_UCI = True` to force fetching.
Dependencies are already installed in this environment; skip the notebook's
optional installation cell.

## Check and exit

```bash
python -m pip check
deactivate
```

`requirements.txt` pins direct dependencies. `requirements-lock.txt` records all
installed versions from the validated Python 3.13 environment. To reproduce those
exact package versions, install with `python -m pip install -r requirements-lock.txt`.
The `.venv` folder and generated data artifacts are excluded from Git.
