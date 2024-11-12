# Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases 

## Introduction


This repository provides resources, code, and documentation for the study "*Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases*," presented at *ISMIR 2024*. This study compiles a comprehensive dataset of music copyright infringement cases, aiming to quantify and analyze melodic similarity through advanced Natural Language Processing (NLP) techniques. This approach facilitates a more objective and scalable analysis of musical similarity, addressing both legal and perceptual aspects in assessing substantial similarity in copyright cases.

The core dataset, *Music Copyright Infringement Cases (MCIC)*, drawn from multiple authoritative sources—including the Music Copyright Infringement Resource (MCIR), *Lost in Music* by Westminster Law School, and recent updates from Yuan (2023)—comprises 116 cases categorized as *Infringed*, *Denied*, or *Settled*. The *MCIC* includes detailed summaries of each case, providing essential insights for computational assessment of melody similarity and enhancing transparency in copyright analysis. [MCIC List](https://docs.google.com/spreadsheets/d/1dzVled_Zb813IGAzZ-qO2uJJpkGbb-MSfvULyLiIdh8/edit?gid=769190082#gid=769190082)

Our methods employ advanced Natural Language Processing (NLP) techniques, including a *Mel2Word* approach, which tokenizes melodies using Byte Pair Encoding (BPE). We calculate similarity scores based on embedding distances that capture semantic meaning, applying our proposed weighting system: the modified Tversky measure and TF-IDF weighting. This approach reflects word salience, importance, and uniqueness at the element level.

The tutorial provides a step-by-step guide to these processes, using practical examples of two songs and includes code for the modified Tversky Measure to compute individual element scores.

Please refer to the full paper for an in-depth analysis of our findings and methodology [[Paper Link]](https://drive.google.com/uc?export=download&id=1WGaNhVIV2MWEcRnyc7S0pV_AjB27z7dQ).

## Dataset Description

We compiled a comprehensive dataset of copyright infringement cases from multiple sources:

- **Music Copyright Infringement Resource (MCIR):** [MCIR](https://blogs.law.gwu.edu/mcir/)
- **Lost in Music by Westminster Law School:** [Lost in Music](https://www.lostinmusic.org/)
- **Yuan (2023):** Includes metadata with perceptual data. [Repository Link](https://github.com/comp-music-lab/music-copyright)


The final dataset comprises 116 cases (Infringed: 32, Denied: 66, Settled: 18).

For more details on the transcription process and additional results, refer to the [Supplementary Document](https://docs.google.com/document/d/1LxcY9rqn1MepNODICntibbvZvVgO7M4fb09eALphJTE/edit?usp=sharing), which includes the following appendices:

- **Appendix 1:** Dataset Description of Melodic Copyright Cases
- **Appendix 2:** Data Statistics
- **Appendix 3:** Weights Statistics
- **Appendix 4:** Extended Case Studies
- **Appendix 5:** Additional Results

For the MCIC list and metadata, which includes:

- Court Decision
- Music Source and Parts
- Reference Sites
- Summary of Judgment Grounds
- Grounds for Dataset Selection from MCIR

see [MCIC List and Metadata](https://docs.google.com/spreadsheets/d/1dzVled_Zb813IGAzZ-qO2uJJpkGbb-MSfvULyLiIdh8/edit?usp=sharing)


## Tutorial
The tutorial covers the following steps using two songs:

1. **Tokenize the melodies into words using Mel2Word**.
2. **Calculate modified-Tversky and TF-IDF scores for each element**.
3. **Compute similarity using a Word2Vec (W2V) model**.

For a detailed step-by-step guide, please refer to the [Tutorial.ipynb](https://colab.research.google.com/drive/1o3f2hh5DdasO4a_4XbVlu5LzWeWn2gP7?usp=sharing).

Additionally, the code for the newly implemented method, `modified Tversky Measure` (measuring individual scores by element), is provided here: [Modified Tversky Measure for Elements.ipynb](https://colab.research.google.com/drive/1jnwict4GttXxo4metpaXbrTFMxY6yqci?usp=sharing).

## Contact
For questions or further information, please contact [saebyul_park@kaist.ac.kr].

---

Please refer to the paper "Quantitative Analysis of Melodic Similarity in Music Copyright Infringement Cases" for a comprehensive analysis and detailed findings.
