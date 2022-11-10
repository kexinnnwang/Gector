# Data Augmentation: Direct Noise

This directory contains the subfolders required to generate pseudo data as mentioned in the paper Improving Grammatical Error Correction via Pre-Training a Copy-Augmented Architecture with Unlabeled Data [pdf](https://aclanthology.org/N19-1014.pdf). 

## Running Script

To run direct noise augmentation do as follows:

1. Enter the directories containing the `noise.sh` script: `cd <dir>/`
2. Execute by running: `./noise.sh`
3. Enter the directory containing the noised data `cd noiseddata`
3. Concatenate the noise-injected files to obtain the respective `.src` and `.tgt` files: \
`cat train_1b_1.src train_1b_2.src train_1b_3.src  >  train.src` \
`cat train_1b_1.tgt train_1b_2.tgt train_1b_3.tgt  >  train.tgt`
4. Run the BART model as previously, but replacing the train `.src` and `.tgt` files with the ones generated here
