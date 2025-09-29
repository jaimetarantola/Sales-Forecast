# Setup Instructions

Steps to recreate my analysis environment.

---

## 1. Activate virtual environment
```bash
.venv\Scripts\activate   # Windows
# or
source .venv/bin/activate   # Mac/Linux
```

---

## 2. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

For exact reproducibility:
```bash
pip install -r requirements.lock.txt
```

---

## 3. Register kernel with Jupyter
```bash
python -m ipykernel install --user --name=.venv --display-name "Python (.venv)"
```

---

## 4. Launch Jupyter Lab
```bash
jupyter lab
```

---

## 5. Data location
Raw data should be placed here:
```
Sales-Forecast\data\data_raw\train.csv
```

---

## 6. Run the notebook
Open and run:
```
notebooks/SF_Modeling.ipynb
```
