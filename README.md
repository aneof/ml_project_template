# ML_Project_Template
Template for new ML projects, ranging from data extraction and modeling to deployment, inspired from various other Github sources, mainly Cookiecutter Data Science.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    ├── data
    │   ├── external       <- Data from third party sources as well as newly acquired data (e.g. new categories).
    │   ├── interim        <- Intermediate transformed data (preprocessing experiments etc.).
    │   ├── processed      <- The final, canonical data sets that are used for model training.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               
    │   ├── code           <- Documenting everything in src (e.g. with a Sphinx project) 
    │   │                     (advanced projects only, class/function docstrings are usually enough)
    │   │
    │   ├── data           <- Schemas, column descriptions etc.
    │   │
    │   ├── media          <- images or videos relevant to the project
    │   │
    │   └── references     <- Data dictionaries, manuals, and all other explanatory materials. 
    │                         (e.g. URLs to third-party library docs, Medium articles about a useful trick we implemented etc.)
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │                         (when needed to be locally stored for experiments)
    │
    ├── notebooks          <- Jupyter notebooks for exploration, experimentation and pre-deployment testing
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── src                <- Source code for use in this project. (All python files except notebooks)
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data from raw sources - annotations
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations (e.g. confusion matrix)
    │       └── visualize.py
    │
    └── tests              <- Testing data, code, outputs
        ├── data_validation
        │
        └── unit

--------