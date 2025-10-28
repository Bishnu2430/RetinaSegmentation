# Kaggle Retina Segmentation

Retina blood vessel segmentation project using deep learning.

## Repository Structure

```
├── train/              # Training dataset (images and masks)
├── test/               # Test dataset (images and masks)
├── files/              # Model checkpoints (tracked with Git LFS)
├── results/            # Final segmentation results
├── ode_unet_results/   # ODE U-Net model results and checkpoints
├── RetinaSegmentation.ipynb  # Main notebook
└── FlowChart.mmd       # Workflow diagram
```

## Git LFS

This repository uses Git LFS for large model checkpoint files (*.pth). Make sure you have Git LFS installed:

```bash
git lfs install
```

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd KaggleRetina
```

2. Pull LFS files:
```bash
git lfs pull
```

## Large Files

The following files are tracked with Git LFS:
- `files/checkpoint.pth` (119M)
- `ode_unet_results/ode_unet_best.pth` (12M)
