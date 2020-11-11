# deepsolar-v2
Reimplementation of DeepSolar using Keras and TensorFlow 2.x

## Setup instructions

1. Clone this repository:
    ```
    git clone https://github.com/aidan-fitz/deepsolar-v2.git
    ```
2. Download the dataset from Academic Torrents using a BitTorrent client.
    - Training set: [SPI_train.tar.gz](https://academictorrents.com/details/8649f33cf8d661cbf3290bd4216c6ac637b777e0)
    - Test set: [SPI_eval.tar.gz](https://academictorrents.com/details/0a3344160f3bb1b6a82f2552cf8503d25e1b6b48)
    - Validation set: [SPI_val.tar.gz](https://academictorrents.com/details/f0977a00ca9d61eefdfa232515ac6690d3b56fc5)
3. Extract each of these files into the folder where your repository is:
    ```
    cd deepsolar-v2
    tar xzvf SPI_train.tar.gz
    tar xzvf SPI_val.tar.gz
    tar xzvf SPI_eval.tar.gz
    ```
    Your directory structure should look like this:
    ```
    deepsolar-v2/
    |- SPI_train/
    |- SPI_val/
    |- SPI_eval/
    |- [repository contents]
    ```
4. Create a virtual environment and activate it (requires Python 3.x):
    ```
    python3 -m venv env
    source env/bin/activate
    ```
5. Install the requirements:
    ```
    pip3 install -r requirements.txt
    ```

## Running

To run any of the Jupyter notebooks in this repository, run:
```
jupyter notebook
```
