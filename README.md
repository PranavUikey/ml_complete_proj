# ml_complete_proj


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/PranavUikey/ml_complete_proj/tree/main
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n end_2_end_ml_project python=3.10.16 -y
```

```bash
conda activate end_2_end_ml_project
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/PranavUikey/ml_complete_proj.mlflow \
MLFLOW_TRACKING_USERNAME= PranavUikey \
MLFLOW_TRACKING_PASSWORD=b164a979bd8248b638f9af447e9b059ea588b82a \
python script.py

Run this to export as env variables:
```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/PranavUikey/ml_complete_proj.mlflow

export MLFLOW_TRACKING_USERNAME=PranavUikey 

export MLFLOW_TRACKING_PASSWORD=b164a979bd8248b638f9af447e9b059ea588b82a

```