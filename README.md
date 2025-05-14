# D-FINE & DEIM Pretrained Models and Dataset Preparation

This repository provides pretrained models for **D-FINE** and **DEIM**, along with datasets and conversion scripts for training and evaluation. It includes:

- VOC and COCO-format datasets
- Pretrained model weights
- Utility script for data restructuring

## Contents

### 📂 Datasets
- `PASCAL-VOC-2007-1/`: Original dataset in Pascal VOC format.
- `PASCAL_VOC_2007_COCO_Format/`: Dataset converted to COCO format for compatibility with various deep learning frameworks.

### 📜 Scripts
- `convert_restructure.ipynb`: A Jupyter notebook for converting and restructuring the dataset formats as needed (e.g., Pascal VOC to COCO).

### 🧠 Pretrained Models
- `deim_dfine_hgnetv2_s_coco_120e.pth`: Pretrained model for D-FINE/DEIM using HGNetV2 architecture, trained on COCO for 120 epochs.
- `dfine_s_coco.pth`: Pretrained D-FINE model on COCO.

## Getting Started

1. **Clone this repository**
   ```bash
   git clone https://github.com/nekloyh/VOC_2007_in_Coco_format.git
   cd VOC_2007_in_Coco_format
2. **Download or Prepare Data**
   
Ensure the datasets are in the correct format. You can use the `convert_restructure.ipynb` notebook to convert between formats if needed.
