# Biomedical-Named-Entity-Recognition-through-transfer-learning-and-asymmetric-tritraining

This repository contains the notebooks used for our research project based on improving biomedical named entity recognition using pre-training and asymmetric tri-training.

## Datasets

In our experiments, we used four different, publicly available biomedical named entity recognition datasets, each encompassing a separate entity domain. These include the BC2GM corpus, BC4CHEMD corpus, NCBI-disease corpus, and S800 corpus.  The entities in any of the datasets are not type-annotated.

## Notebooks

1. Data Preprocessing: For data preprocessing, run the Data Preprocessing notebook.

2. Baseline Model: For creating the baseline model, run the BiLSTM-CRF notebook.

3. Asymmetric Model: For running the proposed model, run the Asymmetric Tritraining notebook.

## References

1. https://github.com/dmis-lab/biobert

2. https://metatext.io/datasets/biocreative-ii-gene-mention-recognition-(bc2gm)

3. https://biocreative.bioinformatics.udel.edu/resources/biocreative-iv/chemdner-corpus/

4. https://www.ncbi.nlm.nih.gov/research/bionlp/Data/disease/

5. https://species.jensenlab.org/
