# Data

Q-HCC - Quality-assured data set for hepatocellular carcinoma.

## heiData

The dataset is available on heiDAta: [doi:10.11588/DATA/IKFTTQ](https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/DATA/IKFTTQ)

One way to download this dataset is to go to the link, then click on the CTimage.zip file, then "Access file" to download the zipfile.

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

To download the dataset from heiData using Pooch:

```python
import pooch

downloader = pooch.DOIDownloader()
downloader("doi:10.11588/data/IKFTTQ/CTimage.zip", output_file="CTimage.zip", pooch=None)
```
