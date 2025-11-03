# Prediction of change in Protein-Protein Interactions upon point mutations
## Course: Applied Molecular Biophysics
    - Code: 1MB518
## Supervisors: 
    - Hugo Gutiérrez de Terán (main)
    - David Sjöberg (daily)
    - Lucien Koenekoop (sometimes :D )

## Short Description
Protein-protein interactions (PPIs) are at the very core of many biological processes such as signal transduction, metabolic regulation and enzymatic complexes.

Accurately predicting the strength of such interactions is a problem that has been under investigation for a long time (REF Janin 1975, Lewis 1992) with various approaches. 
Understanding the effect of point mutations on binding affinity could elucidate the targets for drug discovery and disease modeling. 

## Course Aim
* Plan and carry out a biotechnological project with the aim to investigate  the dynamics, interactions and/or structures of biomolecules.
* Critically analyze, value and summarize the  results obtained and present them in writing as well as orally for different target groups.
* Carry out well-founded scientific, social and ethical assessments of all parts of the project.
* Search, evaluate and use the scientific literature in subjects that lie within the scope of the course and implement this knowledge in the framework of the project.

### Project Aim

The aim of this project is to develop machine learning approaches for PPI affinity predicition. 
This is an *open-ended* and *student-driven* project, your interests will influence the outcome and direction of this project. 

### Ingredients for a well structured Project Plan

* Course Requirements 
* Time limit 
* Previous/Similar work
* Which question are we trying to answer?  

### Suggested reading:
Some suggested articles can be found in the `/lit` folder. 

Brief overview of suggested articles can be found below:

contact_based_PPI.pdf - Bonvin 2015, predicting PPI strength using contact types (polar/apolar) (charged/polar) and is in essence highligting that structural features are important. The 

ESM2 - A protein language model that can predict protein structure. Transformer style model (i.e ChatGPT similar). The interesting part (not mentioned in the paper)
is that the embeddings are information dense and can be used for more than predicting structure. 

geoppi - self-supervised learning scheme to learn geometric representations from protein structures then apply simple ML model for ddG prediction

PPAP - Geometric features using GNN + sequence features using protein language model + attention. (From what I have read is the best predictor out there)

PPB_affinity - Compiled dataset of available sources for protein protein binding. 

PPI_graphomer - graph transformer + language model 

ProAffinity-GNN - Graph representations + language models for binding affinity. Also curates a new dataset. 

ProTrans - Protein language model. In my short empirical testing this has had most useful embeddings

Pytia-PPI - multitask learning and self-distillation, KNN GNN model with geometrical features

SKEMPI V2 - Benchmark dataset of protein protein binding upon mutations 
### Code
In `/code/example` is example code to help you get started on machine learning and neural networks

