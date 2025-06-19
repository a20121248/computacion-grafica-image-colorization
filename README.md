# 🎨 Image Colorization with Deep Learning
This project explores different architectures (CNNs, Autoencoders, and GANs) for converting grayscale images into color images using PyTorch.

## 🧪 Features
- CNN-based image colorization
- Autoencoder-based image colorization
- GAN-based colorization with realistic results
- Google Colab-compatible notebooks
- Experiment logs and results saved for comparison

## 📁 Structure
image-colorization/
│
├── data/
│   ├── raw/                # Original grayscale and color images
│   ├── processed/          # Resized or preprocessed data
│   └── samples/            # Example inputs and outputs for visual inspection
│
├── notebooks/
│   ├── 01_cnn_colorization.ipynb
│   ├── 02_autoencoder_colorization.ipynb
│   └── 03_gan_colorization.ipynb
│
├── experiments/
│   ├── logs/               # Save model training logs here (loss, metrics)
│   ├── models/             # Store .pth files or checkpoints
│   └── results/            # Store inference outputs (grayscale vs colorized)
│
├── utils/
│   ├── data_loader.py      # Data loading and augmentation
│   ├── visualization.py    # Image display utilities
│   └── metrics.py          # PSNR, SSIM, etc.
│
├── train/                  # Training logic
│   ├── train_cnn.py
│   ├── train_autoencoder.py
│   └── train_gan.py
│
├── inference/              # Inference and demo scripts
│   └── run_inference.py
│
├── requirements.txt
└── README.md

## 🚀 How to Start

1. Clone the repo:
```bash
git clone https://github.com/yourusername/image-colorization.git
2. Open a notebook in Google Colab:
- notebooks/01_cnn_colorization.ipynb
- notebooks/02_autoencoder_colorization.ipynb
- notebooks/03_gan_colorization.ipynb
3. Upload sample grayscale images to data/raw/.
4. Run the cells to train or test.
