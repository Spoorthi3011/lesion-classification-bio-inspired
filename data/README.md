
# Dataset — DERM12345

## Source
**DERM12345: A Large, Multisource Dermatoscopic Skin Lesion Dataset with 40 Subclasses**  
Yilmaz et al. — *Scientific Data*, 2024  
Paper DOI: [10.1038/s41597-024-04104-3](https://doi.org/10.1038/s41597-024-04104-3)  
Dataset DOI: [10.7910/DVN/DAXZ7P](https://doi.org/10.7910/DVN/DAXZ7P)

## About
- 12,345 high-resolution dermatoscopic images from 1,627 patients
- 40 subclasses across 5 super classes and 15 main classes
- Includes melanocytic and non-melanocytic, benign and malignant lesions
- Pre-split: 9,860 training / 2,485 test images
- License: Creative Commons Attribution 4.0 (CC BY)

## Download
Download from Harvard Dataverse:
https://doi.org/10.7910/DVN/DAXZ7P

Place downloaded images in:
data/raw/DERM12345/

## Structure (after download)
data/
├── raw/
│   └── DERM12345/
│       ├── images/
│       └── metadata.csv
└── processed/
    ├── train/
    ├── test/
    └── class_map.json
