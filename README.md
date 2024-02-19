# Brain Tumor MRI Analysis with Gemini Pro Vision

This repository contains a dataset of MRI scans used for the detection of brain tumors. The dataset, sourced from Kaggle, includes a variety of MRI images that can be instrumental in training machine learning models for medical diagnostic processes.

## Dataset

The dataset from Kaggle includes MRI images that are labeled based on the presence of brain tumors. For detailed information and to download the dataset, please visit the [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Gemini Pro Vision - Proof of Concept

We are utilizing Google's Gemini Pro Vision to process the MRI images in this dataset. The purpose is to create a proof of concept that can assist radiologists in generating template reports.

The Python code snippet included in this repository demonstrates how to use the Gemini Pro Vision model to analyze MRI images and generate preliminary medical reports, which can then be reviewed and finalized by medical professionals.

## Usage

1. Set your `GOOGLE_API_KEY` in the environment.
2. Process the MRI images using the Gemini Pro Vision model.
3. Generate a medical report for each image.

Below is a conceptual example of how the output might look:

### Example Reports

- **Case 1**: A report for a patient diagnosed with glioblastoma.
`* **Patient:** A 55-year-old male with a history of hypertension and diabetes.
* **Chief complaint:** The patient presents with a 2-week history of progressive headaches and nausea.
* **MRI findings:** The MRI shows a large, enhancing mass in the right frontal lobe of the brain. The mass is causing a significant amount of edema and mass effect.
* **Diagnosis:** The patient is diagnosed with a glioblastoma.
* **Treatment:** The patient is started on chemotherapy and radiation therapy.`
- **Case 2**: A report for a patient with metastatic breast cancer.
- **Case 3**: A report for a patient with a subarachnoid hemorrhage.

## Contributing

Contributions to this project are welcome. Please ensure that you update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
