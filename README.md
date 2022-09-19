# MSRF-Net_TensorFlow

This is an unofficial code of [MSRF-Net](https://arxiv.org/pdf/2105.07451.pdf).

## Model

MSRF-Net is able to exchange multi-scale features of varying receptive fields using a Dual-Scale Dense Fusion (DSDF) block.

MSRF sub-network uses multiple DSDF blocks in sequence to perform multi-scale fusion. This allows the preservation of resolution, improved information flow and propagation of both high- and low-level features to obtain accurate segmentation maps.

## Dataset

Four datasets :

- Kvasir-SEG
- CVC-ClinicDB
- 2018 Data Science Bowl (DSB) Challenge
- ISIC 2018 Challenge

## Data Preparation

- make directory named "data/your_dataset_name"

- make three sub-directories "train" "val" "test"

- Put images under directory named "images"

- Put masks under directory named "masks"

## Testing

For testing the trained model run these sections:

- Prequisites
- Helper functions
- Data Prepration
- Model
- Loss
- Load model
- visualization -> choose your desired image index to perform segmentation
