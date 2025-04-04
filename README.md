# Formation analyse de doonées en python 2025 CRNL

Ce repo contient le materiel de la formation analyse de donnée en python du CRNL 2025





## procédure d'installation avec l'outils **uv**


1. On macOS and Linux. Open a terminal and do
   `$ curl -LsSf https://astral.sh/uv/install.sh | sh`
1. On windows. Open a terminal using **CMD** in the windows menu and do
   `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
2. Exit the terminal and open it again.
3. Download with right click and save this file corresponding in "Documents" folder:
    * [`requirements.txt`](https://raw.githubusercontent.com/crnl-lab/Formation_2025_Python_data_analyse/main/requirements.txt)
4. open terminal or **CMD**
5. `uv venv env_formation --python 3.12`
6. For Mac/Linux `source env_formation/bin/activate` (you should have `(env_formation)` in your terminal) or for Powershell `env_formation\Scripts\activate`
7. `uv pip install -r Documents/requirements.txt`


## Programme

**9 avril 2025**
   
   * **intro python/anaconda** Sam 20min
   * **jupyter/jupyterlab vs IDE** Sam 20min
   * **Base_language** Alexandra 1h
   * **loop_index_slice** Anne 45min
   
   * **numpy_base** Alexandra 30min
   * **numpy_indexing** Anne 45min
   * **numpy_advance** Alexandra  40min
   * **matplotlib_base** Anne 1h


**10 avril 2025**

  * **scipy_overview.ipynb** Alexandre 30min
  * **file_manipulation** Alexandre 45min
  * **pandas_base** Alexandre/Valentin 45min
  * **pandas_exo** Alexandre/Valentin 1h

  * **seaborn_base + pingouin** Alexandre/Valentin 20min
  * **neo** Sam 15min
  * **ephyviewer** Sam 15min
  * **Exo avec EEG** Jules 1h00
  * **MNE overview** Jules 1h00


**11 avril 2025**
  
   * **sklearn** Jules 30min
   * **skimage** Sam 10min
   * **networkx** Jules 15min 
   * **plotly** Sam 10min
   * **Formula_statsmodels** Jules 15min
   * **xarray** Valentin 20min
   * **torch** Sam 20min

   
   torch

Horaires:
 * 9h30 - 10h45
 * 11h00 - 12h45
 * 13h45 - 15h15
 * 15h30 - 17h00
