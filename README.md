# edge-services
Open source generic services (e.g. data base connection) used for working with edge sensors

## Usage
Typical usage is within a RHODS Standard Data Science Notebook image, with pip installs inside the notebook as needed. 

However, `requirements.txt` is provided with full Python packages and versions for usage (tested with python 3.8) outside of RHODS/ODH.

## Structure
```
├── LICENSE                   
├── READ.md
├── anomaly_data_service.py      # Postgres query methods for anomaly table 
├── connection_pool_singleton.py # Start here for Postgres database connection pooling methods
├── examples.ipynb               # Usage examples for query methods
└── requirements.txt 
```



