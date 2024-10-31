# Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases 

## Introduction

This repository contains the dataset and code used in the paper "Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases" presented at ISMIR 2024. The dataset includes 116 cases of melodic infringement (MIDI files, sheet music), and the code employs the Tversky index for similarity analysis. Additionally, this study utilizes natural language processing (NLP) techniques to measure melodic similarity objectively.

Note: The site is still under construction.


## Dataset Description

We compiled a comprehensive dataset of copyright infringement cases from multiple sources:

- **Yuan (2023):** Includes updated metadata with perceptual data.
- **Music Copyright Infringement Resource (MCIR):** [MCIR](https://blogs.law.gwu.edu/mcir/)
- **Lost in Music by Westminster Law School:** [Lost in Music](https://www.lostinmusic.org/)

The final dataset comprises 116 cases (Infringed: 33, Denied: 66, Settled: 17).

For more details on the transcription process and additional results, refer to the [Supplementary Document](https://docs.google.com/document/d/1LxcY9rqn1MepNODICntibbvZvVgO7M4fb09eALphJTE/edit?usp=sharing), which includes the following appendices:

- **Appendix 1:** Dataset Description of Melodic Copyright Cases
- **Appendix 2:** Data Statistics
- **Appendix 3:** Weights Statistics
- **Appendix 4:** Additional Results
- **Appendix 5:** Extended Case Studies

For the MCIC list and metadata, which includes:

- Court Decision
- Music Source and Parts
- Reference Sites
- Summary of Judgment Grounds
- Grounds for Dataset Selection from MCIR

see [MCIC List and Metadata](https://docs.google.com/spreadsheets/d/1eBYHDWRLVL-3-Ze28-dyPLcJHIEUETiFUZzf_fGZ6uU/edit?usp=sharing).


## Tutorial
The tutorial covers the following steps using two songs:

1. **Tokenize the melodies into words using Mel2Word**.
2. **Calculate Tversky and TF-IDF scores for each element**.
3. **Compute similarity using a Word2Vec (W2V) model**.

For a detailed step-by-step guide, please refer to the [Tutorial.ipynb](https://colab.research.google.com/drive/1o3f2hh5DdasO4a_4XbVlu5LzWeWn2gP7?usp=sharing).

Additionally, the code for the newly implemented method, `modified Tversky Measure` (measuring individual scores by element), is provided here: [Modified Tversky Measure for Elements.ipynb](https://colab.research.google.com/drive/1jnwict4GttXxo4metpaXbrTFMxY6yqci?usp=sharing).

## Contact
For questions or further information, please contact [saebyul_park@kaist.ac.kr].

---

Please refer to the paper "Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases" for a comprehensive analysis and detailed findings.
