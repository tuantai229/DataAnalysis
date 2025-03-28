### Create conda env
`conda create -n data_analysis python=3.10`

### Activate data_analysis env
`conda activate data_analysis`

### Install packages
`pip install jupyter ipykernel numpy pandas matplotlib seaborn`

### Register env with jupyter
`python -m ipykernel install --user --name=data_analysis`