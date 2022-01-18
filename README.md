# How to run project

<img 
src="https://github.com/danielwetan/data-ipm-jakarta/blob/master/screenshot.png"
alt="Folium IPM Jakarta output map"
style="float: center;"
/>

## Setup the environment

This project is using Python `3.8.10` and then `venv` to create environment:
```console
$ python3 -m venv env
$ source ./env/bin/activate
$ jupyter notebook
```

## Install required packages
```console
pip install -r requirements.txt
```

## Project files
- `data-ipm-jakarta.csv`: Indeks Pembangunan Manusia (IPM) DKI Jakarta Tahun 2014 in the CSV format
- `data-kabupaten-jakarta.json`: Map region of DKI Jakarta in JSON format
- `notebook.ipynb`: Jupyter notebook containing the project code
- `output_map.html`: Saved map in the HTML format

## Author
Nama: Daniel Saputra

NIM: 1304211006

Email: danielwetan@student.telkomuniversity.ac.id

Source Data:

https://data.jakarta.go.id/dataset/data-indeks-pembangunan-manusia-menurut-kabupaten-kota-administrasi/resource/c073e709-95a5-4d44-9333-a417db32f2c1