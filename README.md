# GIE-AHP: A gamification experiences evaluation framework

This repository accompanies the academic article describing **GIE-AHP**, a methodological framework for the validation of results in gamified educational experiences. It contains the materials, tools, and experimental results employed throughout the study, providing transparency, reproducibility, and resources for future research.  

## Repository Structure  

### 1. `parameters_study.xlsx`  
This spreadsheet compiles the set of parameters evaluated in the methodology. The parameters were extracted through a systematic review and organized for inclusion in a SQL database, which is leveraged by one of the tools within this repository.  

### 2. `systematic_review.xlsx`  
This file contains the aggregated data from the systematic review of the academic literature. It includes statistics and classifications derived from the reviewed articles, serving as the empirical foundation for the parameter set and subsequent analyses.  

### 3. `InformationGatheringTools/`  
This directory provides models of surveys designed to collect the data necessary for applying the GIE-AHP methodology. These instruments can be adapted to different contexts and reused in related validation studies.  

### 4. `ProjectPony/`  
This directory contains the outputs of the experimental study conducted to evaluate the methodology. It is organized into two subdirectories:  

- **`Tools/`**  
  - *Survey Makers*: A web-based tool for digital collection of survey responses.  
  - *`GIE-AHP-Solver.xlsx`*: An automated Excel-based tool. By inputting the data gathered from the *InformationGatheringTools*, the solver generates a comprehensive report including all parameters, calculated results, and visual representations derived through GIE-AHP.  

- **`Results/`**  
  This folder includes the outcomes of the five experimental trials performed. Each trial is presented in an individual subdirectory containing:  
  - The raw survey results,  
  - The adjusted *GIE-AHP-Solver* file for that experiment,  
  - The final reports with the validated results.  

## Purpose  

The materials provided here aim to support researchers, practitioners, and educators interested in applying or extending the **GIE-AHP validation methodology**. By offering both the tools and the experimental data, this repository serves as a reference for methodological rigor, reproducibility, and adaptation to new contexts.  

## Citation  

If you use or build upon the contents of this repository, please cite the associated article:  

> *[Full academic reference to be inserted once available]*  
