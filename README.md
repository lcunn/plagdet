# PlagDet - a music plagiarism detection prototype framework

This is the codebase corresponding to my summer project report, titled "A deep embedding system for melodic plagiarism detection", completed for the course MSc Data Science and Machine Learning at UCL. It is roughly broken down into three parts, corresponding to the experiments in the report.

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/lcunn/plagdet.git
   cd plagdet
   ```

2. Create and activate the Conda environment:
   ```
   conda env create -f environment.yml
   conda activate plagdet
   ```

3. Unzip the data folder:
   ```bash
   unzip data.zip
   ```

## Experiment 1: Training a perturbation-invariant symbolic melody embedding model

This experiment involves training a Siamese network 
