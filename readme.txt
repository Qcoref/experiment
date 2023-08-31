This repository hosts resources related to our paper, "Towards Transparency in Coreference Resolution: A Quantum-Inspired Approach."

**Model Download:**
To obtain the model, you can visit the following link: [Model Download Link](https://drive.google.com/file/d/1LawKyfZCJXQkbdz9jrxc1xSJ-LzPjdl0)

**Average Runtime:**
The estimated runtime for each model is approximately 48 hours.

**Model Parameters:**
Each model comprises 2693 parameters.

**Hyperparameters:**
For hyperparameters, the initial learning rate (a) is set to 0.1, the initial parameter-shift scaling (c) is set to 0.06, and the stability constant (A) is set to 20.

**Training and Evaluation:**
The training and evaluation process involves 2000 epochs of Simultaneous Perturbation Stochastic Approximation (SPSA).

**Random Seed Values:**
We utilized the following random seed values for experimentation: 0, 10, 50, 77, 100, 111, 150, 169, 200, 234, 250, 300, 350, 400, 450. Among these, the best seed performance was observed with seed value 450.

**Dataset Splitting:**
The datasets are split into training, validation, and test sets, with a random distribution of 60%, 20%, and 20% respectively.

**Dataset Labeling:**
In the datasets, rows with even numbers are labeled as 1, and rows with odd numbers are labeled as 0. For label 0, the wrong referent is utilized, whereas for label 1, the correct referent value is used.

**Dataset Balance:**
The datasets have been balanced in terms of class distribution.

**Parsing and Data Quality:**
A minor subset of sentences could not be parsed successfully. Consequently, these sentences were excluded from the training and testing phases.
