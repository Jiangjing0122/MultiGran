# MultiGran
The code of the MultiGran model.
Article: MultiGran-SMILES: Multi-Granularity SMILES Learning for Molecular Property Prediction


Package description
data
Dataset used in the experiments in the article

MultiGran
Python files to build a MultiGran model for molecular property predictions.

BACE_sample.py
An example for usage

# Requirements

pytorch                   1.7.1

rdkit                     2020.09.1

tqdm                      4.62.3

python                    1.7.1

numpy                     1.21.2

# Datasets
BACE, BBBP, HIV, Tox21, and ToxCast from MoleculeNet[1], FDA and LogP from ZINC[2]. All the datasets are classification tasks. 

# Run code

python main.py

Datasets can be changed in the 222 line of main.py.


# Reference
[1] Wu, Z., Ramsundar, B., Feinberg, E. N., Gomes, J., Geniesse, C., Pappu, A. S., Leswing, K., and Pande, V. (2018). Moleculenet: a benchmark for molecular
machine learning. Chemical science, 9(2), 513–530.

[2] Sterling, T. and Irwin, J. J. (2015). Zinc 15–ligand discovery for everyone. Journal of chemical information and modeling, 55(11), 2324–2337.
The code of the MultiGran model will be upload after the paper be accepted.
