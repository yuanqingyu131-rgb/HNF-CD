# HNF-CD

HNF-CD is a public benchmark dataset for academic research on high-resolution forest change detection.

This dataset is constructed to support the evaluation of forest change detection methods under complex multi-temporal forestry scenarios, including both same-season and cross-season image pairs. The dataset provides bi-temporal optical image pairs, binary change masks, and predefined training/testing splits.

## Download

The complete HNF-CD dataset can be downloaded from the release page:

[Download HNF-CD.zip from GitHub Releases](https://github.com/yuanqingyu131-rgb/HNF-CD/releases/download/v1.0.0/HNF-CD.zip)

Alternatively, please go to:

`Releases` → `HNF-CD v1.0.0` → `Assets` → `HNF-CD.zip`

Please note that the green `Code` → `Download ZIP` button only downloads the repository files, such as the README, and does not download the full dataset archive.

## Dataset Description

HNF-CD focuses on binary forest change detection. In this dataset, changed regions correspond to substantive cross-category semantic conversions among forest-related land-cover categories, while phenological variation, illumination differences, seasonal appearance changes, and other non-semantic variations are retained as unchanged hard negative samples.

The dataset is intended to support research on robust forest change detection, especially under challenging conditions such as seasonal discrepancy, complex forest boundaries, shadow interference, and heterogeneous background changes.

## Dataset Contents

The released dataset includes:

- Bi-temporal optical image pairs;
- Binary change masks;
- Predefined training and testing splits.

The image pairs are organized as follows:

- `A`: pre-event / first-temporal images;
- `B`: post-event / second-temporal images;
- `label`: binary change masks.

All image files are provided in TIFF format.

## Directory Structure

The dataset is organized using the following structure:

```text
HNF-CD/
├── train/
│   ├── A/
│   ├── B/
│   └── label/
└── test/
    ├── A/
    ├── B/
    └── label/
```

## Usage

HNF-CD is released for non-commercial academic research and educational use.

Researchers may use this dataset for developing, training, evaluating, and comparing forest change detection methods. When using HNF-CD in publications, reports, presentations, or derivative research, please cite the corresponding paper.

## Citation

If you use HNF-CD in your research, please cite the following paper:

```bibtex
@article{yuan2026tbrmamba,
  title   = {TBR-Mamba: Hierarchical Transfer Learning and Boundary-Aware Spatiotemporal Interaction Network for Forest Change Detection},
  author  = {Yuan, Jingxiang and Tan, Xiaobo and Gong, Gufeng and Zhou, Guoxiong and Zhu, Ming'e},
  journal = {IEEE Transactions on Geoscience and Remote Sensing},
  year    = {2026},
  note    = {Manuscript under review}
}
```

Please update the citation information according to the final published version of the paper.

## Data Source and Attribution

The original optical imagery used for constructing HNF-CD is derived from the Google Earth platform.

Users should comply with the applicable terms, conditions, and attribution requirements of the original imagery source when using this dataset.

## Terms of Use

By downloading or using HNF-CD, users agree to the following terms:

1. HNF-CD is intended for non-commercial academic research and educational use only.
2. Users should cite the corresponding paper when using this dataset.
3. Users should not use the dataset for commercial purposes without obtaining any necessary permissions from the relevant rights holders.
4. Users are responsible for ensuring that their use of the dataset complies with applicable laws, institutional policies, and source-data terms.
5. Redistribution, commercial use, or use beyond academic research should comply with the relevant source-data policies and applicable laws.
6. The dataset is provided "as is" without warranty of any kind.

## Disclaimer

HNF-CD is provided to facilitate academic research on forest change detection. The authors make no warranties regarding the completeness, accuracy, or fitness of the dataset for any particular purpose. The authors shall not be held responsible for any consequences arising from the use of the dataset.

## Contact

For questions regarding HNF-CD, please contact:

Jingxiang Yuan  
Email: 20233231@csuft.edu.cn
