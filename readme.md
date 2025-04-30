# Skin Cancer Classification

## Overview
This repository contains code for a deep learning model that classifies skin lesions into 7 different categories using the HAM10000 dataset. The model employs EfficientNet-B0 architecture.

## Authors
- TRAORE Sy Lucien
- Hanna Hellgren
- Sanae Dariouche



## Quick Start
1. Clone the repository
```bash
git clone https://github.com/yourusername/skin-cancer-classification.git
cd skin-cancer-classification
```

2. Set up environment
```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  
pip install -r requirements.txt
```

3. Open and run the Jupyter notebook
```jupyter notebook Skin_Classification.ipynb```

## Key Features
- EfficientNet-B0 architecture (5.3M parameters)
- Mixed precision training
- Weighted sampling for class imbalance
- Data augmentation techniques
- 86% accuracy on HAM10000 validation set


## Acknowledgements
This project was completed as part of the Deep Learning course at Data ScienceTech Institute (DSTI), Applied MSc in Data Science and Artificial Intelligence, 2024-2025.

For more detailed information about the model architecture, training methodology, and results, please refer to the project report.