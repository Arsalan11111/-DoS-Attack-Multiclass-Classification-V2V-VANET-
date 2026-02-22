

# DoS Attack Multiclass Classification (V2V / VANET)

This repository contains a Jupyter notebook that loads a VANET/V2V dataset and trains a **multiclass classifier** to detect different **DoS / attack types** using **Random Forest**.

## What’s inside
- `DoS_Attack_Multiclass_Classification.ipynb`  
  Main notebook: data loading → cleaning → label encoding → training + evaluation.

## Dataset / Files Needed
The notebook expects these files (paths may be updated depending on your setup):

- `filtered_data.csv` (main dataset file)
- (optional) `veremi-dos.zip` if you’re downloading/extracting the dataset first

If your files are not in the same location as the notebook, update the paths in the notebook:
```python
df = pd.read_csv('/content/filtered_data.csv')
