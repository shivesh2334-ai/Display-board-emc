# ECG Data Analysis Pipeline

This repository contains a complete ECG analysis pipeline implemented in Python and designed for Google Colab. It demonstrates data simulation, preprocessing, model building, training, and an application class for ECG analysis.

## Features

- **Synthetic ECG Data Generation** (similar to PTB-XL format)
- **Data Preprocessing**: Z-score normalization, train/val/test splitting
- **Deep Learning Model**: CNN for multi-label ECG classification
- **Training Pipeline**: EarlyStopping, ReduceLROnPlateau, ModelCheckpoint callbacks
- **Analysis Application**: End-to-end prediction, risk assessment, clinical recommendations, ECG visualization

## Getting Started

### Prerequisites

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Usage

Open the notebook `ECG_data_pipeline_2.ipynb` in Google Colab or Jupyter Notebook. Run the cells step by step to:

1. **Install requirements and set up environment**
2. **Generate synthetic ECG data**
3. **Preprocess data**
4. **Build and train the CNN model**
5. **Analyze and visualize ECG signals**

### File Structure

- `ECG_data_pipeline_2.ipynb`: Main notebook with all steps
- `requirements.txt`: List of dependencies
- `README.md`: This file

## Notes

- The notebook uses synthetic data for quick demonstration. For real-world analysis, download and preprocess the PTB-XL dataset or other ECG datasets.
- The model is for educational/demo purposes and is not intended for clinical use.

## References

- [PTB-XL ECG Dataset](https://physionet.org/content/ptb-xl/1.0.1/)
- [wfdb Python Package](https://github.com/MIT-LCP/wfdb-python)

## License

This repository is for educational purposes.
