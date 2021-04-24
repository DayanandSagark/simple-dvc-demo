Create env


```bash
conda create -n wineq python=3.7 -y
```
Activate env

```bash
conda activate wineq
```
Install requuiremnts.txt

```bash
pip install -r requirements.txt

```
download data set from 
``` bash
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5
```
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add . && git commit -m "first commit" 
```
```bash
git remote add origin https://github.com/DayanandSagark/simple-dvc-demo.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
```bash
dvc repro
```
```bash
dvc params diff
```
```bash
dvc scores diff
```
```bash
dvc metrics show
```
```bash
dvc metrics diff
```
```bash 
tox
```
tox rebuilding 
```bash
tox -r
```
```bash
pytest -v
```
setup commands
```bash
pip install -e .
```
build your own pkg
```bash
python setup.py sdist bdist_wheel
```

create an artifcats folder

mlflow server command -

mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 127.0.0.1 -p 1431