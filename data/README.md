# Dataset Instructions

The raw dataset is not included in this repository.

This project uses the public Kaggle dataset associated with the ADA-Net paper:

**Aerial Imagery for Dead Tree Segmentation**
Author: Mete Ahishali
Source: Kaggle
Associated paper: *ADA-Net: Attention-Guided Domain Adaptation Network with Contrastive Learning for Standing Dead Tree Segmentation Using Aerial Imagery*

## How to Obtain the Dataset

Download the dataset directly from Kaggle:

```text
https://www.kaggle.com/datasets/meteahishali/aerial-imagery-for-standing-dead-tree-segmentation
```

After downloading, extract the archive locally.

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

## Notes

The raw dataset is intentionally excluded from version control because it is an external public dataset and should be downloaded from its original source.

The following files and folders should not be committed to GitHub:

```text
archive.zip
*.zip
USA_segmentation/
data/USA_segmentation/
dataset/
```

This keeps the repository lightweight and avoids redistributing external image data.
