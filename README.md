# U-Net Image Segmentation

## Overview

U-Net is a convolutional neural network architecture designed for biomedical image segmentation. This implementation focuses on segmenting images using U-Net to achieve precise boundary detection in the target objects. This repository provides a complete framework to train, validate, and infer using the U-Net model with a custom dataset.  
![image](https://github.com/user-attachments/assets/54c8bbae-c3b3-4513-afd7-72f4d10fa8f6)  
   

## Features

- **Image Segmentation**: Effectively segments images using a U-Net architecture.
- **Custom Dataset Support**: Easily integrate and use your datasets.
- **Batch and Single Image Inference**: Perform predictions on multiple images or a single image.
- **Easy to Use**: Run the training and inference with simple command-line instructions.

## Getting Started

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/bibasrairockz/UNET.git
    cd UNET
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Dataset Preparation

This implementation uses the Carvana dataset for training. You can download it from [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge/data).

Place the dataset in the `./data` directory.

## Usage

1. **Training the Model**:
   To train the model, run:
   ```bash
   python main.py
   ```
```bash
UNET/
│
├── LICENSE
├── README.md
├── carvana_dataset.py         # Custom dataset class for Carvana
├── inference.py               # Inference script for predictions
├── main.py                    # Main training script
├── unet.py                    # U-Net model definition
└── unet_parts.py              # Building blocks of U-Net (e.g., DoubleConv, DownSample, UpSample)
```


