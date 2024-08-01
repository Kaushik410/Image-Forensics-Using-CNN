# Dataset Instructions

## Downloading the Dataset

The dataset used in this project can be downloaded from Kaggle. Follow the instructions below to download and prepare the dataset.

### Step-by-Step Instructions

1. **Visit the Kaggle Dataset Page**:
   Go to [CASIA Dataset on Kaggle](https://www.kaggle.com/datasets/sophatvathana/casia-dataset).

2. **Sign in to Kaggle**:
   If you do not have a Kaggle account, you will need to create one. Sign in to your Kaggle account.

3. **Download the Dataset**:
   - Click on the "Download" button on the Kaggle dataset page.
   - Save the downloaded file to your local machine.

4. **Extract the Dataset**:
   - Unzip the downloaded file if it is in a compressed format (e.g., .zip).
   - Move the extracted dataset files to the `data/` directory in your project.

### Example Directory Structure

After downloading and extracting the dataset, your project directory should look like this:

```
Image_Forensics_Project/
│
├── data/
│   ├── casia/
│       ├── CASIA1/
│       └── CASIA2/
│
├── models/
│   ├── model1/
│       └── image_forensics_model.keras
│
├── notebooks/
│   ├── Image_Forensics_Training.ipynb
│   └── Image_Forensics_Prediction.ipynb
│
├── scripts/
│   ├── download_data.py
│
├── README.md
└── .gitignore
```

### Additional Information

For more information on how to use the dataset with the provided notebooks and models, please refer to the [README.md](README.md) file.
