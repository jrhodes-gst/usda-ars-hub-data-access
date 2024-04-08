# usda-ars-hub-data-access

This guide demonstrates how to run the notebook files in this repository in an Ubuntu Linux environment.

Install Python3.11 and activate a new virtual environment:
```bash
$ sudo apt-get install python3.11
$ python3.11 -m venv pyenv
$ source pyenv/bin/activate
```

Install Python library dependencies:
```bash
$ pip3 install -r requirements.txt
```

Run Jupyter Notebooks and open the browser to http://localhost:8888/lab:
```bash
$ jupyter notebook
```

