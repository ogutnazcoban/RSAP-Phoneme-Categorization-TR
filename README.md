# The Role of Timbre, Phoneme Type, and Listening Context in Phoneme Categorization

This repository contains the source code and materials for the psychoacoustic experiment developed as part of the Master's thesis titled **"The Role of Timbre, Phoneme Type, and Listening Context in Phoneme Categorization"**.

The experiment is web-based, developed using the **jsPsych (v7.3.3)** library, and utilizes original auditory stimuli based on **Turkish phonemes**.

## ⚠️ Legal Notice and Usage Permissions

The codes and **especially the auditory stimuli (sound files)** contained in this repository were developed within the scope of a Master's thesis conducted at Ankara Medipol University.

* Copying, distributing, or using these materials (code or sound files) for academic or commercial purposes in other studies is **strictly subject to permission**.
* If you wish to use any part of this work for purposes other than reviewing the code, please contact the researcher via the email address below.

📧 **Contact:** [ogutnaz@gmail.com](mailto:ogutnaz@gmail.com)

---

## Project Summary

The aim of this research is to investigate the effect of timbral characteristics of speech sounds (phonemes) on auditory perception and categorization in different listening environments (quiet and noisy). The study is established on natural speech recordings selected and manipulated in accordance with the **phonetic structure of the Turkish language**.

**Researchers:**
* **Principal Investigator:** Öğütnaz Çoban (MSc Student, Ankara Medipol University)
* **Supervisor:** Assoc. Prof. Dr. Mustafa Yüksel (Ankara Medipol University)
* **External Advisor:** Prof. Dr. Adam Tierney (Birkbeck, University of London)

## Experiment Material: Turkish Phonemes

All target and distractor sounds used in this experiment were created by processing recordings taken from **native Turkish female speakers**.

* **Target Sounds:**
    1.  **Stop Consonant:** /K/ (Consistent with Turkish phonotactics)
    2.  **Fricative:** /F/
    3.  **Vowel:** /I/ (The unrounded close back vowel typical to Turkish)
* **Acoustic Manipulations:** The sounds were modified based on Attack Time, Spectral Centroid, and Spectral Flux parameters.

## Installation and Running

To run this experiment on your local machine:

1.  Clone this repository or download as ZIP.
2.  Ensure that the audio files (`.wav`) are in the root directory.
3.  **Important:** Due to browser security policies (CORS), audio files may not load if you simply double-click `index.html`. Please use a local server (e.g., VS Code Live Server) to run the experiment.

## Data Output

Upon completion, the system automatically downloads two `.csv` files:
1.  **Raw Data:** Contains response times (RT) and accuracy for each trial.
2.  **Summary Analysis:** Contains a summary of success rates and pass/fail status per block.

## Technologies Used

* **[jsPsych v7.3.3](https://www.jspsych.org/):** Experiment control flow.
* **HTML5/CSS3:** User interface.
* **MATLAB:** (Used for the generation and manipulation of the auditory stimuli).

---
© 2025 Öğütnaz Çoban. All rights reserved.
