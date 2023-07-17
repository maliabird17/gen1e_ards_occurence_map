# Predicting ARDS occurrence in the USA for 2023

### Overview of Repo: 
- `gen1e_project`: Data Folder: includes the processed csv used for the heatmap (`visualization_data.csv`), as well and original data from the CDC, NIS, and County Health Rankings used in this analysis. 
- `heatmap-processing.ipynb`: main Python notebook used for data processing, modelling, and prediction.
- `interactive_heatmap.ipynb`: Python notebook used to generate the interactive heatmap.

### Replicating Results 

All data pipelines are configured to access the `gen1e_project` folder on your desktop containing all the data needed for the project as it is currently organized in the repository. Downloading the `gen1e_project` folder to your desktop and ensuring all requirements from the specified file are downloaded should allow the notebook's results to be replicated. 

Getting started: 

```
python3.9 -m venv your_venv # recommended python version is 3.9.16
source bin/activate/your_venv
pip install -r requirements.txt
```

### Running the visualization 

```
python3.9 -m venv your_venv # recommended python version is 3.9.16
source bin/activate/your_venv
pip install -r requirements.txt
```

Then, run `interactive_heatmap.ipynb` and open http://127.0.0.1:8000/ on your local browser to view and use the heatmap. 
