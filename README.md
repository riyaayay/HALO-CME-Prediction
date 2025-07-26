
# Halo CME Detection using ATSFusion (VELC + ASPEX)

This notebook implements a hybrid CNN-LSTM architecture ("ATSFusion") to detect Halo CMEs using image data from the VELC instrument and time-series proton flux data from ASPEX.

## 🔍 Dataset
- *VELC*: FITS-format solar images
- *ASPEX*: CDF-format proton flux time-series
> ⚠ Datasets not included in this repo due to size. Please contact [your email or mention organization] for access or use your own formatted data.

## 🚀 How to Run
1. Install dependencies in a Jupyter/Colab environment.
2. Update the VELC_DIR and ASPEX_DIR variables to point to your local dataset.
3. Run all cells.
