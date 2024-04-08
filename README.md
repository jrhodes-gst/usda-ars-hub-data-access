# usda-ars-hub-data-access

This guide demonstrates how to run the notebook files in this repository in an Ubuntu Linux environment.

Install Python3.11 and activate a new virtual environment:
```bash
$ sudo apt-get install python3.11
$ python3.11 -m venv pyenv
$ source pyenv/bin/activate
```

Clone this repository locally:
```bash
$ git clone https://github.com/jrhodes-gst/usda-ars-hub-data-access.git
```

Install Python library dependencies:
```bash
$ cd ./usda-ars-hub-data-access/
$ pip3 install -r requirements.txt
```

Run Jupyter Notebook command:
```bash
$ jupyter notebook
```

Open a browser to http://localhost:8888/lab and navigate to this repository's notebook files in the jupyter lab file explorer on the left.
