# BAM-DataStore-Documentation
A documentation page for BAM Data Store.

The documentation page is build using [MkDocs](https://www.mkdocs.org/). To view the documentation locally, first create and activate your virtual environment:
```sh
python3 -m venv .pyenv
source .pyenv/bin/activate
```

Make sure `pip` is upgraded to its latest version by running:
```sh
pip install --upgrade pip
```

Install the requirements:
```sh
pip install -r requirements.txt
```

Once the installation is finished, you can launch the documentation server:
```sh
mkdocs serve
```

The output looks like:
```sh
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  [14:07:47] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO    -  [14:07:47] Serving on http://127.0.0.1:8000/
```

Simply click on `http://127.0.0.1:8000/`. The changes in the `md` files of the documentation are inmediately reflected when the files are saved (the local web will automatically refresh).
