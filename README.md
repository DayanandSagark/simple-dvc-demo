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
