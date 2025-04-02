# Formation analyse de doonées en python 2025 CRNL


## procédure d'installation avec le 'outils **uv**


1. On macOS and Linux. Open a terminal and do
   `$ curl -LsSf https://astral.sh/uv/install.sh | sh`
1. On windows. Open a powershell and do
   `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
2. exit session and log again.
3. Download with right click and save this file corresponding in "Documents" folder:
    * [`requirements.txt`](https://raw.githubusercontent.com/crnl-lab/Formation_2025_Python_data_analyse/main/requirements.txt)
4. open terminal or powershell
5. `uv venv env_formation --python 3.12`
6. For Mac/Linux `source env_formation/bin/activate` (you should have `(env_formation)` in your terminal) or for Powershell `env_formation\Scripts\activate`
7. `uv pip install -r Documents/requirements.txt`
