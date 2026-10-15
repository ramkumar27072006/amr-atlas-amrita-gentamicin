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

## Scientific scope

The phenotype records contain laboratory-method metadata but were computationally curated from BV-BRC; they are not independent experimental susceptibility results confirmed by this project. Results are exploratory and do not establish clinical performance. AMRFinderPlus is independent determinant evidence; zero hits do not mean susceptible. The published page displays saved cohort results only. New FASTA analysis requires a separate backend and is not performed by GitHub Pages.

## Publish with GitHub Pages

This repository is a self-contained static site: `index.html` is the entry point. Enable Pages from the `main` branch, root folder, in the repository's Settings → Pages. No genome FASTA files, trained model binaries, or HPC executables are needed to serve the dashboard.
