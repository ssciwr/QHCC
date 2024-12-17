# Welcome to Q-HCC

Some text about what this is...

## Quickstart

Our example notebook shows how you can download a dataset from heiData.

### Online

You can run our example notebook online without installing anything on your computer.

<div class="grid cards" markdown>

-   __Google Colab__

    ---

	[Open In Colab](https://colab.research.google.com/github/ssciwr/QHCC/blob/main/notebooks/example.ipynb){ .md-button }

    (Google account required)

-   __Binder__

    ---

	[Open in Binder](https://mybinder.org/v2/gh/ssciwr/QHCC/HEAD?labpath=notebooks%2Fexample.ipynb){ .md-button }
</div>

### Locally

Alternatively you can run it on your computer.

First clone the repository using git:

```bash
git clone https://github.com/ssciwr/QHCC
cd QHCC
```

Then install the required Python libraries and launch JupyterLab:

=== "pip"
    ```bash
    pip install -r requirements.txt
    jupyter lab notebooks/example.ipynb
    ```

=== "conda"
    ```bash
    conda env create -f environment.yml
    conda activate QHCC
    jupyter lab notebooks/example.ipynb
    ```

=== "micromamba"
    ```bash
    micromamba env create -f environment.yml
    micromamba activate QHCC
    jupyter lab notebooks/example.ipynb
    ```
