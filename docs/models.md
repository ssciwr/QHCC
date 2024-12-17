# Models

Example models and data are provided at [github.com/ZhaoWenzhao/QHCC](https://github.com/ZhaoWenzhao/QHCC).

In order to run the provided example scripts, you will need to use Python 3.8 or 3.9, and install the required Python libraries:

=== "pip"
    ```bash
    pip install jupyter numpy pandas pooch pyradiomics simpleitk scikit-learn xgboost
    ```

=== "conda"
    ```bash
    conda env create -n QHCC2 jupyter numpy pandas pooch python radiomics::pyradiomics simpleitk scikit-learn xgboost -c conda-forge -c radiomics
    conda activate QHCC
    ```

=== "micromamba"
    ```bash
    micromamba env create -n QHCC2 jupyter numpy pandas pooch python radiomics::pyradiomics simpleitk scikit-learn xgboost -c conda-forge -c radiomics
    micromamba activate QHCC
    ```
