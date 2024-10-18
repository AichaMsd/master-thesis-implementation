# Investigating the Impact of Prompt Engineering Techniques on Energy Consumption in LLMs
This repository accompanies the Master thesis on Investigating the Impact of Prompt Engineering Techniques (PETs) on Energy Consumption in LLMs. 

Author: Aicha Moussaid

Supervisor: Phuong T. Nguyen

Co-Supervisor: Riccardo Rubei

## Repository Structure 

This repository is organized as follows:

* `Datasets_Creation.ipynb` contains code for creating the main datasets used in the experiments for each PET. 
* `Datasets` folder contains the resulting datasets by the above notebook if you don't wish to run it.
* `Experiment_Execution.ipynb` is the main notebook to run to launch the experiments on a specific PET dataset.
* `Evaluation_Analysis.ipynb` contains the code for the evaluation phase, which outputs different graphs for computational efficiency and performance evaluations, based on the files provided in the `Results` folder.
* `Results` folder contains 4 different folders for each PET. Each PET folder contains the generated outputs from the LLM and the emissions file output by CodeCarb onof each repetition (since we conduct 5 repetitions). 

