# Dataset Instructions

The raw dataset is not included in this repository.

This project uses the public Kaggle dataset associated with the ADA-Net paper:

**Aerial Imagery for Standing Dead Tree Segmentation**
Author: Mete Ahishali
Source: Kaggle
Associated paper: *ADA-Net: Attention-Guided Domain Adaptation Network with Contrastive Learning for Standing Dead Tree Segmentation Using Aerial Imagery*

## How to Obtain the Dataset

Download the dataset directly from Kaggle:

```text
https://www.kaggle.com/datasets/meteahishali/aerial-imagery-for-standing-dead-tree-segmentation
```

After downloading, extract the archive locally.

Only download the dataset from the original Kaggle source and follow the dataset provider's terms.

## Expected Folder Structure

The notebook expects the dataset to be arranged as follows:

```text
data/
└── USA_segmentation/
    ├── RGB_images/
    ├── NRG_images/
    └── masks/
```

Each sample should have corresponding RGB, NRG, and mask files.

## Split Files

The repository includes lightweight split files under the root-level `splits/` folder:

```text
splits/train.csv
splits/train.txt
splits/val.csv
splits/val.txt
```

These files are used to make the train/validation split reproducible. They do not replace the raw dataset. The image and mask files still need to be downloaded separately from Kaggle.

## Files Not Tracked

The raw dataset and local archives should not be committed to GitHub.

Examples of files and folders that should remain local:

```text
archive.zip
*.zip
USA_segmentation/
data/USA_segmentation/
dataset/
datasets/
raw/
```

This keeps the repository lightweight and avoids redistributing external image data.

## Notes

Only lightweight documentation is tracked in this folder.

The notebook and result files assume that the dataset has already been downloaded and placed in the expected local structure before execution.
