# b11_moviewise
Recommandation model with versionning via MLflow 
```
project/
│
├── img/
│   ├── raw/    # Raw images directory
│   │   ├── yes/
│   │   └── no/
│   │
│   └── splits/    # Splitted data directory
│       ├── test/
│       │   ├── yes/    # Images with tumor
│       │   └── no/    # Images without any tumor
│       │
│       ├── train/
│       │   ├── yes/
│       │   └── no/
│       │
│       └── val/
│           ├── yes/
│           └── no/
│
├── functions/ # functions directory
│      ├── load_functions.py
│      ├── rename_split.py
│      └── plot_image.py
│
├── .gitignore
├── main.ipynb    # Main notebook
└── README.md

```
