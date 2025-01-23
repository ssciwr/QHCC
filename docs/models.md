# Models

A paper draft is available at [arXiv:2501.11535](https://arxiv.org/abs/2501.11535). The objective of this paper is to provide a baseline for performing multi-modal data classification on a novel open multimodal dataset of hepatocellular carcinoma (HCC), which includes both image data (contrast-enhanced CT and MRI images) and tabular data (the clinical laboratory test data as well as case report forms).

Example models and pre-processed data are provided at [github.com/ZhaoWenzhao/QHCC](https://github.com/ZhaoWenzhao/QHCC).

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
