
# Data Packaging for Pretraining LLM

## 📌 Dataset Information

The preprocessed dataset **(`preprocessed_dataset.parquet`)** is available under the [Releases](https://github.com/omarnahdi/data-packaging/releases). Please download it manually before running the Jupyter Notebook.

## 🔽 How to Download & Set Up the Dataset

1.  Navigate to the [Releases](https://github.com/omarnahdi/data-packaging/releases) section of this repository.
2.  Download the `preprocessed_dataset.parquet` file.
3.  Move the downloaded file into the `data/` directory.

    ```sh
    mkdir -p data && mv preprocessed_dataset.parquet data/
    ```

## 🚀 Running the Data Packaging Notebook

Once the dataset is placed correctly, open and run `data packaging.ipynb` in Jupyter Notebook:

```sh
jupyter notebook "data packaging.ipynb"
```

Ensure that all required dependencies are installed before execution:

```sh
pip install -r requirements.txt
```

## ❗ Important Notes

*   The dataset is not included in the repository due to size limitations.
*   Make sure the dataset is correctly placed inside the `data/` directory before executing the notebook.
*   If you encounter any issues, ensure that the dataset file name and location are correct.

Happy coding! 🚀
