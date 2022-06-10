# Genre Classfication

## Project Description

- To be Added

## Files
```
LICENSE
MLproject
README.md
check_data
   |-- MLproject
   |-- conda.yml
   |-- conftest.py
   |-- test_data.py
conda.yml
config.yaml
download
   |-- MLproject
   |-- conda.yml
   |-- download_data.py
evaluate
   |-- MLproject
   |-- conda.yml
   |-- run.py
main.py
preprocess
   |-- MLproject
   |-- conda.yml
   |-- run.py
random_forest
   |-- MLproject
   |-- conda.yml
   |-- run.py
segregate
   |-- MLproject
   |-- conda.yml
   |-- run.py
```
## Running Files
- ```$ mlflow run [github URL] -v [version] -P ...```
- e.g.
```
$ mlflow run [github URL] \
             -v 1.0.0 \
             -P hydra_options="main.project_name=remote_execution"
```
