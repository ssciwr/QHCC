# Models

Example models and data are provided at [github.com/ZhaoWenzhao/QHCC](https://github.com/ZhaoWenzhao/QHCC).

In order to run the provided example scripts, you will need to use Python 3.8 or 3.9, and install the required Python libraries.

## pip & requirements.txt
You can do this with pip, by first [downloading requirements.txt](requirements.txt) and then running:

=== "pip"
    ```bash
    pip install -r requirements.txt
    ```

## conda & environment.yml

You could also use conda or micromamba, by first [downloading environment.yml](environment.yml) and then running:

=== "conda"
    ```bash
    conda env create -f environment.yml
    conda activate QHCC
    ```

=== "micromamba"
    ```bash
    micromamba env create -f environment.yml
    micromamba activate QHCC
    ```

## direct pip/conda

Alternatively you can install the required Python libraries directly:

=== "pip"
    ```bash
    pip install jupyter numpy pandas pooch pyradiomics simpleitk scikit-learn xgboost
    ```

=== "conda"
    ```bash
    conda env create -n QHCC jupyter numpy pandas pooch python radiomics::pyradiomics simpleitk scikit-learn xgboost -c conda-forge -c radiomics
    conda activate QHCC
    ```

=== "micromamba"
    ```bash
    micromamba env create -n QHCC jupyter numpy pandas pooch python radiomics::pyradiomics simpleitk scikit-learn xgboost -c conda-forge -c radiomics
    micromamba activate QHCC
    ```
