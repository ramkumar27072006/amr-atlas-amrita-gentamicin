# AMR Atlas | AMR-ML-HPC

A static research dashboard for exploratory gentamicin resistance label evaluation in 231 *Pseudomonas aeruginosa* genome records.

## Team

RAMKUMAR R · PRAGALYA M · YOUVASHREE K  
Amrita Vishwa Vidyapeetham, Coimbatore Campus

## Dashboard contents

- Cohort and sequence QC overview
- Held-out metrics and confusion matrices for Logistic Regression, Random Forest, and XGBoost
- Training-only five-fold variability
- Serial, OpenMP, and MPI feature extraction timings
- AMRFinderPlus results and a searchable per-genome evidence explorer
- Browser-side FASTA QC and exact SHA-256 lookup for uploaded cohort genomes

## Scientific scope

The phenotype records contain laboratory-method metadata but were computationally curated from BV-BRC; they are not independent experimental susceptibility results confirmed by this project. Results are exploratory and do not establish clinical performance. AMRFinderPlus is independent determinant evidence; zero hits do not mean susceptible. The upload panel computes basic QC locally and can identify an exact byte-level match to a saved cohort genome. It does not upload sequence files. For a new genome, model inference and AMRFinderPlus interpretation require a separate backend; GitHub Pages does not run those analysis tools.

## Publish with GitHub Pages

This repository is a self-contained static site: `index.html` is the entry point. Enable Pages from the `main` branch, root folder, in the repository's Settings → Pages. No genome FASTA files, trained model binaries, or HPC executables are needed to serve the dashboard.
