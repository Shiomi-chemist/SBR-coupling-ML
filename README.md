# SBR-coupling-ML
Structure-Based Regression (SBR) modeling code for coupling reaction yield prediction using molecular fingerprints and ElasticNet regression.

## Contents
- Fingerprint generation (Morgan, Avalon, RDK, MACCS, Topological Torsion)
- ElasticNet modeling with cross-validation
- External validation scripts

## Requirements
- Python 3.10
- RDKit
- scikit-learn
- pandas
- numpy
- matplotlib

## Usage
1. Prepare a CSV file containing SMILES and yields.
2. Run fingerprint generation notebook.
3. Run ElasticNet modeling notebook.
4. Optional: run external validation notebook.

## Notes
All calculations correspond to the Supporting Information of the associated manuscript.
