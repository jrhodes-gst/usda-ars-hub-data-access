# usda-ars-hub-data-access

These scripts can be executed using Python 3.11 in a virtual environment.

Here is an example of the install and set up on Ubuntu Linux:
```bash
$ sudo apt-get install python3.11
$ python3.11 -m venv pyenv
$ source pyenv/bin/activate
```

Several Python libraries are required to run the scripts:
```bash
$ pip3 install arcgis==2.2.0.2 pandas==2.1.4 dask[dataframe]
```

For demonstration purposes, the scripts are provided as Jupyter Notebook files.

To open a Jupyter Notebook environment run this command and open a browser at http://localhost:8888/lab:
```bash
$ jupyter notebook
```

Clone this repository and copy the notebook files to your local folder that Jupyter Notebook was opened from to access the files there.
