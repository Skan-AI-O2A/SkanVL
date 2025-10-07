# 🧠 SkanVL Installation Guide

## 📋 Prerequisites
Before proceeding, ensure you have the following:
- **Python 3.10 or higher**  
- **CUDA-compatible GPU** (recommended for optimal performance)  
- **Conda or Miniconda** (for environment management)

---

## ⚙️ Installation Steps

> **Note:** You **do not** need to download or clone the full repository.  
> Only download the `requirements.txt` file and follow the steps below.

### 1️⃣ Create a Conda Environment
Create a new conda environment with Python 3.13:

```bash
conda create -n skanvl python=3.13
```

### 2. Activate the Conda Environment
```bash
conda activate skanvl
```

### 3. Download the requiremnets.txt
Download the requirements.txt file from the project source (no need to clone the repo).

```bash
wget https://path-to-your-requirements-file/requirements.txt
```
(Or simply copy it manually if provided to you.)

### 4. Install Dependencies
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
