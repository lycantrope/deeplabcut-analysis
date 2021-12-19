# A package for analyzing the data from DeepLabCut


# how to use this script 
- Install python 3.9 using miniconda only for install python and pip
```
conda create -n -y your_env_name python=3.9 
conda activate your_env_name
```

- create a venv in the director your want 
- It will create a .venv folder in your enviornment
```
conda activate your_env_name
python3.9 -m venv .venv
```

- Activate the enviroment
- - for windows
```
source ./.venv/Scripts/activate
python3.9 -m pip install -U -r requirements.txt
python3.9 -m pip install .
```

- - for Linux/MacOs
```
source ./.venv/bin/activate
python3.9 -m pip install -U -r requirements.txt
python3.9 -m pip install .
```


