# Deep Learning for Music Genre Classification

**Project Assignment by:** Hedi Hadiji  
**Date:** October 2025  
---

## Files

- **`main.ipynb`** – Baseline model implementation for music genre classification.  
- **`extension.ipynb`** – Contains improvements added to the baseline model, including data augmentation and label smoothing.

---

## Installation

Install required packages:
```python
pip install -r requirements.txt
```

Install PyTorch suitable for your device:
Visit PyTorch official website to select the correct command based on your OS, Python version

The project expects the **FMA small dataset (`fma_small`)** to be located in the **parent folder** of this repository.
For example, if your repository folder is:
/path/to/music_genre_classification_repo
then the dataset should be:
/path/to/fma_small

This ensures that the following lines in the code work properly:
```python
Path("../fma_small") / folder / filename
Path("../fma_small").rglob("*.mp3")```
