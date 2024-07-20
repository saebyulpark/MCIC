# Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases

## Introduction

This repository contains the dataset and code used in the paper "Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases" presented at ISMIR 2024. The dataset includes 116 cases of melodic infringement (MIDI files, sheet music), and the code employs the Tversky index for similarity analysis. Additionally, this study utilizes natural language processing (NLP) techniques to measure melodic similarity objectively.

## Dataset Description

We compiled copyright infringement cases from a variety of sources to create a comprehensive dataset:

1. **Yuan (2023)**: Provided updated metadata with perceptual data.
2. **Music Copyright Infringement Resource (MCIR, 2018)**: Available at [MCIR Blog](https://blogs.law.gwu.edu/mcir/)
3. **Lost in Music by Westminster Law School**: Available at [Lost in Music](https://www.lostinmusic.org/)

The final dataset includes a total of 116 cases (Infringed: 33, Denied: 66, Settled: 17).

For detailed information on the transcription process, please refer to this document: [Transcription Details](https://docs.google.com/document/d/1LxcY9rqn1MepNODICntibbvZvVgO7M4fb09eALphJTE/edit)

For the full description and selection criteria of all cases, please refer to the following document: [Case Description and Selection](https://docs.google.com/spreadsheets/d/1eBYHDWRLVL-3-Ze28-dyPLcJHIEUETiFUZzf_fGZ6uU/edit?usp=sharing)

## Tutorial
The tutorial covers the following steps using two songs:

1. **Tokenize the melodies into words using Mel2Word**.
2. **Calculate Tversky and TF-IDF scores for each element**.
3. **Compute similarity using a Word2Vec (W2V) model**.

For a detailed step-by-step guide, please refer to the [Tutorial.ipynb](Tutorial.ipynb).

Additionally, the code for the newly implemented method `TV_by_element` (extracting Tversky individual scores by element) is provided here: [TVelement.ipynb](TVelement.ipynb).

## Contact
For questions or further information, please contact [saebyul_parkl@kaist.ac.kr].

---

Please refer to the paper "Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases" for a comprehensive analysis and detailed findings.
