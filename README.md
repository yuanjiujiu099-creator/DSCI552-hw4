# DSCI 552 Homework 4

Name: Xiaoyun Tang
GitHub Username: Nokiovo099

## Folder structure

- data/AReM: the AReM dataset (7 activity folders, 88 files)
- notebook/Tang_Xiaoyun_HW4.ipynb: my code and answers
- requirements.txt: the Python packages I used

## How to run

1. Install the packages: pip install -r requirements.txt
2. Open notebook/Tang_Xiaoyun_HW4.ipynb and run all cells. The notebook finds the data in ../data/AReM.

Note: the cell in 2(c)i (multinomial L1 logistic regression with cross-validation) is slow. It takes about 30 minutes, because it fits 500 models with the saga solver.
