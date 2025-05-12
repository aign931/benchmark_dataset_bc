# Breast Cancer Variant Benchmark Dataset

This repository contains the code and processed data for constructing a benchmark dataset of breast cancer-related missense variants, annotated with functional prediction scores and population allele frequencies.

## Project Description
This project aims to support the evaluation and interpretation of pathogenicity prediction models (e.g., VARITY, MutScroe, MVP) by providing a standardized, high-confidence dataset.

## Data Sources
- **ClinVar**: https://www.ncbi.nlm.nih.gov/clinvar/
- **dbNSFP v5.1a**: https://www.dbnsfp.org/

## Tools Used
- [Ensembl VEP](https://www.ensembl.org/info/docs/tools/vep/index.html) with Docker
- dbNSFP plugin for VEP
- Python (v3.12.3)
- PowerShell (on Windows)
- Ubuntu 24.04 via WSL2
- R (v4.3.3)
- Conda (Miniconda3)
- GitHub repositories of each model:
   - [VARITY](https://github.com/joewuca/varity).
   - [MutScore](https://github.com/mquinodo/MutScore).
   - [MVP](https://github.com/ShenLab/missense).


## Notes
1. Data is accessible via link in 'Data Scources'.
2. Please refer to the original models for virtual environment configuration.

## License
MIT License

---