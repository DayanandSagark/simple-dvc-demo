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

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

git init

dvc init

dvc add data_given/winequality.csv

git add . && git commit -m "first commit" 