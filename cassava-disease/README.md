# Cassava Disease Classification

## Create the Conda environment

The following command will create the Conda environment inside a sub-directory `./env/`.

```bash
$ conda env create --prefix ./env environment.yml
```

## Download the competition data

After activating the Conda environment the Kaggle command line interface should be available. The following command will download the competition data into the appropriate folder.

```bash
$ kaggle competitions download -c cassava-disease -p data/raw/
