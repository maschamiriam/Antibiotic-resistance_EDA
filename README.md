# Project: Antibiotic Resistance of *E. coli* - Explorative Data Analysis (EDA)

Antibiotic resistance, hence the ability of a certain type of bacteria to withstand the treatment with antimicrobial substances (due to e.g. gene mutations) represents a huge problem for modern medicine. Especially if bacteria like *Escherichia coli*, which are common residents of the microbial flora on the human skin and intestines, are able to resist antibiotics (antimicrobial substances), this can lead to non-healing wound infections or other harmful consequences for the host (human). The development of new antibiotics on the other hand is usually not worth investing for the pharmaceutical industry and prommotes the evolution of additional resistance mutations in the bacterial genomes.  
Therefore, I find it important to investigate the currently available antibiotics for their susceptibiliy to hopefully gain new insides to tackle the rising problem of antibiotic resistance in the healthcare system and found a large public dataset for an explorative analysis.

**Outline** of this EDA Project:
1. **Pre-processing**: Import, clean + standardize (real-world) raw data
2. **Data analysis**: Explorative analysis looking at occurence of antibiotic resistance
3. **Visualization**: Plot results in different graphs to make them more comprehendable
4. **Next steps**: If possible, apply machine learning model for e.g. most frequent genome locations responsible for resistance mutations.

_________________

The **dataset** used for this analysis can be downloaded from: https://www.kaggle.com/datasets/valeriamaciel/e-coli-resistance-dataset/data

This dataset contains 195,000+ raw records of *Escherichia coli* clinical isolates and their antimicrobial susceptibility test results. The data was extracted from the Bacterial and Viral Bioinformatics Resource Center (BV-BRC), a public repository funded by NIAID.
Each entry captures how a specific *E. coli* genome responds to a given antibiotic, along with phenotypic interpretation, lab methods, measurement values (e.g., MIC), and supporting publication links.
