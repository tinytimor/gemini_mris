# Brain Tumor MRI Analysis with Gemini Pro Vision

This repository contains a dataset of MRI scans used for the detection of brain tumors. The dataset, sourced from Kaggle, includes a variety of MRI images that can be instrumental in training machine learning models for medical diagnostic processes.

## Dataset

The dataset from Kaggle includes MRI images that are labeled based on the presence of brain tumors. For detailed information and to download the dataset, please visit the [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Gemini Pro Vision - Proof of Concept

I am utilizing Google's Gemini Pro Vision to process the MRI images in this dataset. The purpose is to create a proof of concept that can assist radiologists in generating template reports.

The Python code snippet included in this repository demonstrates how to use the Gemini Pro Vision model with LangChain to prompt the model to analyze MRI images and generate preliminary medical reports, which can then be reviewed and finalized by medical professionals, such as radiologists. 

## Usage

1. Set your `GOOGLE_API_KEY` in the environment.
2. Process the MRI images using the Gemini Pro Vision model.
3. Generate a medical report for each image.

Below is a conceptual example of how the output might look:

### Example Reports

![Te-gl_0010](https://github.com/tinytimor/gemini_mris/assets/108763451/9325596c-ccc2-4280-a26b-e91565628c7c)
![Audio File](example_radiology_audio.mp3)
**Case 1**

* **Patient:** John Smith
* **Age:** 45
* **Sex:** Male
* **Date:** 01/01/2023
* **Study:** T2 MRI of the brain
* **Diagnosis:** Encephalomalacia

**Findings:**

* There is a large area of encephalomalacia in the right frontal lobe.
* The encephalomalacia is surrounded by a rim of gliosis.
* There is no evidence of mass effect.

**Impression:**

* Encephalomalacia in the right frontal lobe.

**Differential Diagnosis**
* Stroke
* Trauma
* Infection
* Tumor

**Recommendations:**

* The patient should be evaluated by a neurologist.
* The patient should undergo a CT scan of the brain to rule out any other pathology.
* The patient should be started on a course of corticosteroids to reduce inflammation.


## Contributing

Contributions to this project are welcome. Please ensure that you update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
