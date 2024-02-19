# Brain Tumor MRI Analysis with Gemini Pro Vision

This repository contains a dataset of MRI scans used for the detection of brain tumors. The dataset, sourced from Kaggle, includes a variety of MRI images that can be instrumental in training machine learning models for medical diagnostic processes.

## Dataset

The dataset from Kaggle includes MRI images that are labeled based on the presence of brain tumors. For detailed information and to download the dataset, please visit the [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Gemini Pro Vision - Proof of Concept

I am utilizing Google's Gemini Pro Vision to process the MRI images in this dataset. The purpose is to create a proof of concept that can assist radiologists in generating template reports.

The Python code snippet included in this repository demonstrates how to use the Gemini Pro Vision model with LangChain prompt the model to analyze MRI images and generate preliminary medical reports, which can then be reviewed and finalized by medical professionals, such as radiologists. 

## Usage

1. Set your `GOOGLE_API_KEY` in the environment.
2. Process the MRI images using the Gemini Pro Vision model.
3. Generate a medical report for each image.

Below is a conceptual example of how the output might look:

### Example Reports

- **Case 1**: A report for a patient diagnosed with glioblastoma.
- **Case 2**: A report for a patient with metastatic breast cancer.
- **Case 3**: A report for a patient with a subarachnoid hemorrhage.

## Contributing

Contributions to this project are welcome. Please ensure that you update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
