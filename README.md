# CS4248 Final Project: Grammatical Error Correction (GEC)
Group 10 Evan Ang Jia-Jun (A0200591R), I Chieh Chen (A0260551M), Terence Ho Wei Yang (A0196511E), Wang Kexin (A0205324U), Wong Wen Wei Esmanda (A0206353M)

This directory contains the subfolders for our grammatical error correction project. The directory structure is as follows:

- [Preprocess](Preprocess): The raw train, development and test data given for this project in `.m2`  format, preprocessing script to convert the `.m2` files into `.src` and `.tgt` files as well as the preprocessed train, development and test data in their respective directories.
- [BART](BART): Scripts to setup and run BART.
- [T5](T5): Scripts to setup and run T5.
- ['Data Augmentations']('Data Augmentations'): Scripts to generate data augmentation using Direct Noise and the C4_200M dataset used
- [Ensemble](Ensemble): Files to run the ensembling code

Please refer to the README files in the respective folders for detailed instructions on how to run the models.
