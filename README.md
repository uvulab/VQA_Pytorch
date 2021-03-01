# VQA_Pytorch

## Install the followin libraries

- conda install pytorch==1.2.0 torchvision==0.4.0 cudatoolkit=10.0 -c pytorch
- pip install spacy
  - After the instalation of spacy, run: python -m spacy download en
- pip install torchtext==0.2.3
- pip install -U scikit-learn

## Code Locations

- `run_model.py` runs a toy example
- `model.py` contains our models
- `load_dataset.py` loads the dataset set with our format

## Dataset format
```
project
│   README.md
│   file001.txt    
│
└───folder1
│   │   file011.txt
│   │   file012.txt
│   │
│   └───subfolder1
│       │   file111.txt
│       │   file112.txt
│       │   ...
│   
└───folder2
    │   file021.txt
    │   file022.txt
```
