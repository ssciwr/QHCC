# Data

Introduction to the provided datasets.

## heiData

The datasets are stored on [heiData](https://heidata.uni-heidelberg.de/) which also provides a DOI.

Here is an example dataset: [doi:10.11588/data/TKCFEF](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/TKCFEF)

One way to download this dataset is to go to the link, click "Access Dataset", then "Download ZIP".

However if you are then going to use the data from a Python script or jupyter notebook then consider using the [Pooch](https://www.fatiando.org/pooch/latest/) library instead.

## Pooch

[Pooch](https://www.fatiando.org/pooch/latest/) is a Python library for downloading datasets, and it has native support for heiData. To install:

=== "pip"
    ```bash
    pip install pooch
    ```

=== "conda"
    ```bash
    conda install pooch
    ```

To download the example dataset from heiData using Pooch:

```python
from pooch import DOIDownloader

downloader = DOIDownloader()
downloader("doi:10.11588/data/TKCFEF/tiny-data.txt", output_file="tiny_data.txt", pooch=None)
```
