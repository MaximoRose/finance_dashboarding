# finance_dashboarding
Processing yahoo finance data
- Installation, [here](https://pypi.org/project/yfinance/#installation)
- Official documentation, [here](https://pypi.org/project/yfinance/)
- Please, also install the nospam library, [here]

## Configure Conda environment.
Use [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) to set up your kernel.

- Create a conda environment
```
conda create --name shares_dashboarding python=3.11 pandas jupyter seaborn scikit-learn
```

- Activate conda environment
```
conda activate shares_dashboarding 
```

- Install additional libraries
```
pip install yfinance  
pip install requests-cache
```