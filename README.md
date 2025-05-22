# Yeast Of War
## A series of experiments using hardware and wetware olfactory sensors to test yeast quality

### Setup

1. Create a virtual environment
```bash
uv venv
# On Windows
.venv\Scripts\activate
# On Unix or MacOS
source .venv/bin/activate
```

2. Install pytorch and dependencies depending on your system

For CPU only:
```bash
uv pip install -r pyproject.toml --extra cpu
```
For CUDA 12.6:
```bash
uv pip install -r pyproject.toml --extra cu126
```

### Dependencies We're Using

| Dependency   | Purpose                              |
|--------------|--------------------------------------|
| Pytorch      | For machine learning                 |
| Torchvision  | For machine learning                 |
| Torchaudio   | For machine learning                 |
| Numpy        | For general numerical operations     |
| Pandas       | For data manipulation and analysis   |
| Matplotlib   | For plotting                         |
| Joblib       | For saving and loading models        |
| Optuna       | For hyperparameter optimization      |
| Scikit-learn | For machine learning                 |
| Websockets   | For communication                    |
| Pyarrow      | For data storage                     |
| Pyserial     | For serial communication             |
| Rich         | For logging and progress bars        |