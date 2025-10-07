# SkanVL Installation Guide

## Prerequisites
- Python 3.10 or higher
- CUDA-compatible GPU (recommended for optimal performance)
- Conda or Miniconda

## Installation Steps


### 1. Create a Conda Environment
```bash
conda create -n skanvl python=3.13
```

### 2. Activate the Conda Environment
```bash
conda activate skanvl
```


### 4. Downlaod the requiremnets.txt and Install Dependencies
```bash
pip install -r requirements.txt
```

## Verification
To verify the installation was successful, you can run:
```bash
python -c "import transformers; print('Installation successful!')"
```

## Notes
- This project is based on Hugging Face Transformers
- GPU support is recommended for Vision-Language model inference
