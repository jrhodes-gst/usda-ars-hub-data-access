# USDA-ARS Environmental Data Hub Programmatic Data Access with Python

This repository provides example Python notebook scripts for programmatically accessing data from the USDA-ARS Environmental Data Hub.

### How to run in your own environment

1. Install Python3.11 and activate a new virtual environment:
```bash
$ sudo apt-get install python3.11
$ python3.11 -m venv pyenv
$ source pyenv/bin/activate
```

2. Clone this repository locally:
```bash
$ git clone https://github.com/jrhodes-gst/usda-ars-hub-data-access.git
```

3. Install Python library dependencies:
```bash
$ cd ./usda-ars-hub-data-access/
$ pip3 install -r requirements.txt
```

Run Jupyter Notebook command:
```bash
$ jupyter notebook
```

Open a browser to http://localhost:8888/lab and navigate to this repository's notebook files in the jupyter lab file explorer on the left.
