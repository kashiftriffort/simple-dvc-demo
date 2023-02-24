create env
```bash
conda create -n wineq python -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```

download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```bash
git init
```

```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

```
git add .
```

```
git commit -m "first commit"
```

onliner updates for readme
```bash
git add . && git commit -m "update README.md"
```

```bash
git remote add origin https://github.com/kashiftriffort/simple-dvc-demo.git
git branch -M main
git push origin main
```