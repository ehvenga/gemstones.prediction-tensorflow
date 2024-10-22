# Gemstone Identification with TensorFlow

Welcome to the Gemstone Identification project! This project leverages TensorFlow to create a deep learning model that identifies various gemstones using a carefully curated dataset.

## Getting Started

Follow the steps below to set up the model and run the identification process.

### Step 1: Locate the Processed Dataset

Ensure you know the location of the `dataset-processed` folder. This folder contains the preprocessed images that will be used by the model.

## Captured Image

![Image of Gemstone to be Analyzed](capture_image.png 'Image of Gemstone to be Analyzed')

## Prediction Outcome

![Image of Prediction](prediction.png 'Image of Prediction output')

### Step 2: Update Data Directory

Navigate to line 6 in the `template.ipynb` file. Update the `data_dirpathname` variable with the correct path to your `dataset-processed` folder. This is essential to ensure the notebook can locate the dataset.

### Step 3: Execute the Notebook

Run all the cells in `template.ipynb`. This will process the data, train the model, and generate necessary logs to monitor the model's performance.

### Step 4: Load and Test the Model

Use the `template_load.ipynb` notebook to load the trained model. You can test the model by either uploading your own images or using a connected camera to classify gemstone images in real-time.

### Step 5: Verify the Results

Once you have tested the model, verify the classification results to ensure the model is working as expected and providing accurate predictions.

## Requirements

To run this project, ensure you have the following dependencies installed:

- Python 3.8+
- TensorFlow 2.x
- Keras
- OpenCV (for image preprocessing)
- NumPy
- Matplotlib (for visualizations)

You can install the necessary packages by running:

```bash
pip install -r requirements.txt
```
