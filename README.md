# Preprocessing Data

This directory contains the subfolders to generate the data required for the GEC task. The folders are as follows:

-   [Train](Train/): Generate training data
-   [Test](Test/): Generate test data
-   [Development](Development/): Generate development data

The folders contain the original data given for the GEC task in their respective folders. In addition, they contain the python script `m2_to_parallel.py` to convert `.m2` files to `.src` and `.tgt` files. The folders also contain scripts (`preprocess_*.sh`) that preprocess the datasets using the python script.

## Running preprocess scripts

To run the preprocess scripts:

1. Enter the directories containing the script: `cd <dir>/`
2. Replace the file paths to the data directories in `preprocess_*.sh`
3. Execute the files to run the scripts: `./preprocess_*.sh`
