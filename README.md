# Taiwan district distance matrix

A Python Notebook to calculate the distance between districts in Taiwan.

The output file is not actually a matrix, I call it that for lack of a better name.😂

## What are these JSON files?

### `taiwan_district_coordinate.json`

This file contains the coordinates of the districts in Taiwan. It's the input file for the notebook.

The data originates from [tw-area-json/position.json](https://github.com/xue-yuan/tw-area-json/blob/main/position.json).

### `taiwan_district_distance.json`

This file contains the distance between the districts in Taiwan. It's the output file of the notebook. It is 15 MB, so I will not upload it to GitHub. Instead, a zipped version has been uploaded.

If you prefer not to generate the file by running the notebook, you can download and unzip the [taiwan_district_distance.json.zip](taiwan_district_distance.json.zip) file and use it directly.

## Installation

### OS X & Linux

```shell
cd root/path/of/this/repo

python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```

## Run

### GUI

Pick any of the following methods, and use the Python from the `.venv`.

- [Running the Notebook — Jupyter Documentation](https://docs.jupyter.org/en/latest/running.html)
- [Working with Jupyter Notebooks in Visual Studio Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
