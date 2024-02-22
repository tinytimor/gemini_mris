# Brain Tumor MRI Analysis with Gemini Pro Vision & OpenAI Whisper

This repository contains a dataset of MRI scans used for the detection of brain tumors. The dataset, sourced from Kaggle, includes a variety of MRI images that can be instrumental in training machine learning models for medical diagnostic processes.

https://github.com/tinytimor/gemini_mris/assets/108763451/4f980f48-f3ce-4981-8f0c-df91a19c44c8


## Dataset

The dataset from Kaggle includes MRI images that are labeled based on the presence of brain tumors. For detailed information and to download the dataset, please visit the [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

## Gemini Pro Vision & OpenAI Whisper - Proof of Concept

I am utilizing Google's Gemini Pro Vision to process the MRI images in this dataset. The purpose is to create a proof of concept that can assist radiologists in generating template reports.

The Python code snippet included in this repository demonstrates how to use the Gemini Pro Vision model with LangChain to prompt the model to analyze MRI images and generate preliminary medical reports, which can then be reviewed and finalized by medical professionals, such as radiologists. The impact of the work can be help with:

- **Efficiency**: Saves time for medical professionals by automating the initial analysis process
- **Triaging**: Helps prioritize urgent cases by quickly identifying abnormalities
- **Workflow optimization**: Increases efficiency in the healthcare system by streamlining workflows
- **Diagnosis facilitation**: Provides a starting point for further investigation and treatment planning
- **Accuracy and consistency**: Enhances accuracy and consistency in report generation

Once the reports are created, I use OpenAI's Whisper model to generate audio files to allow radiologists to have the flexibility to listen to the radiological reports instead of reading them. This application of Whisper's Text-to-Speech (TTS) model offers several potential impacts and opportunities in the medical field:

- **Learning and Training**: Audio files can be used in educational settings, allowing students to listen to sample reports and familiarize themselves with radiological terminology and diagnosis processes.
- **Patient Communication**: Simplified audio reports could be shared with patients to help them better understand their diagnoses in a more accessible format.
- **Language Translation**: Coupled with language translation models, the Whisper TTS model can generate reports in multiple languages, improving the inclusivity and accessibility for non-English speaking patients and professionals.
- **Documentation and Archiving**: Audio archives of radiological reports can complement written records, offering an additional layer of documentation for clinical cases.

## Usage

1. Set your `GOOGLE_API_KEY` and `api_key` (OpenAI's API Key) in the environment.
2. Process the MRI images using the Gemini Pro Vision model.
3. Generate a medical report for each image in the gemini_w_mri_data.ipynb.
4. Generate an audio file from OpenAI Whisper model in the whisper_audio_report_generation.ipynb.  

Below is a conceptual example of how the output might look:

### Example Reports

![Te-gl_0010](https://github.com/tinytimor/gemini_mris/assets/108763451/9325596c-ccc2-4280-a26b-e91565628c7c)

Audio Generation of Radiology Report Generated from OpenAI's Whisper:

https://github.com/tinytimor/gemini_mris/assets/108763451/36d09240-e7fd-4058-818a-781be05fe6f6

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

### Another Audio Example
https://github.com/tinytimor/gemini_mris/assets/108763451/f03cab29-2ce4-4d75-9dde-f6d003938a5f

## Contributing

Contributions to this project are welcome. Please ensure that you update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
