# README

## Setup jupyter notebook environment in VSCode

````
# my condas environments name is cmapss
conda activate cmapss
conda install ipykernel
python -m ipykernel install --user --name=cmapss --display-name "Python (cmapss)"

# in your environment install
pip install pandas
pip install matplotlib
pip install seaborn
pip install ipynbname
````

## Download data 

Make sure to download the [data](https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data) and add it to the folder ``/data``.

You will have this folder structure then: 

```
├── .gitignore
├── README.md
└── data
    └── CMAPSSData
        ├── readme.txt
        ├── RUL_FD001.txt
        ├── RUL_FD002.txt
        ├── RUL_FD003.txt
        ├── RUL_FD004.txt
        ├── test_FD001.txt
        ├── test_FD002.txt
        ├── test_FD003.txt
        ├── test_FD004.txt
        ├── train_FD001.txt
        ├── train_FD002.txt
        ├── train_FD003.txt
        └── train_FD004.txt
└── notebooks
    ├── README.md
    └── 01_EDA_CMAPSS.ipynb
```

