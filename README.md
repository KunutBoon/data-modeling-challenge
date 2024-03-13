# Data Modeling Challenge
## Project File Structures
The structure of files in this repository is illustrated below
```
ROOT
├── notebook                                  <- Folder for jupyter notebooks
│   └── fraud.ipynb                                 <- Jupyter notebooks contains all the code for data modeling
├── .gitignore
├── README.md
└── requirements.txt                          <- requirement files for library dependencies
```
## System Settings

The python environment is required with libraries listed inside the <code>requirements.txt</code> files in order to successfully execute all the codes. Please make sure that the environment was set up correctly before any execution of the code.

Here are the versions of Conda environment which was used to complete the assignment
```
conda == 23.5.2
python == 3.9.18
```

To easily manage all dependencies, Conda virtual environment is recommended. You can use this command to manage the environment after installing conda (Miniconda 3)

```
conda create --name <env_name> --file requirements.txt    ## create the environment with requirement.txt
conda list                                                ## list all imported packages
conda activate <env_name>                                 ## activate the environment
conda deactivate                                          ## deactivate the environment
```
## Input Data File Structures
A given dataset is needed as a input to run this notebook. The dataset must be stored inside the /data folder since the code will try to access data from that particular folder. Please refer to full-detail information below
```
ROOT
├── data
│   └── FraudDataset.csv  ** the data must be stored inside this directory **
├── notebook
├── .gitignore
└── ....
```

The name of dataset used in the source code are the same as original. No modification on file name is needed.

## Submission Files
There are only 1 Jupyter Notebook files summitted in this repository, including
 - <code>fraud.ipynb</code> : The Jupyter notebook file contains all the code involved with data modeling

As the order of code execution in each Jupyter notebook is designed in sequence, the execution of code could be done cell by cell from the beginning to inspec the output.

If there is any question or issues, please do not hesitate to contact me via email. I would be happy to answer those quesions.