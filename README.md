# HER2-CCD

Receptor protein-tyrosine kinase erbB-2, aka HER2 (Human Epidermal Growth Factor Receptor 2), is a membrane-bound receptor and a type of tyrosine kinase.
HER2 is a key player in cell signaling and the control of cellular growth. Its role in breast cancer has made it an important target for therapeutic drugs.

To read more about HER2 visit this [article by NCBI](https://pmc.ncbi.nlm.nih.gov/articles/PMC4170925/)

# Configuration
To run the juypter notebook make sure all dependencies are installed. All relevant dependencies can be found in the first section of the ipynb file. 

# Analysis

This project focuses on analyzing HER2-related data, with ChEMBL as a primary source for bioactive molecules. [ChEMBL](https://www.ebi.ac.uk/chembl/) provided key information such as compound structures, activity data, and identifiers like SMILES strings, which are essential for cheminformatics workflows. Using RDKit, the notebook computes molecular descriptors and fingerprints to represent the chemical properties of these compounds, enabling the exploration of structure-activity relationships. These descriptors form the foundation for predictive modeling efforts aimed at linking molecular structures to HER2 activity.

The workflow integrates data cleaning, exploratory data analysis, and machine learning to develop predictive models. Visualizations and metrics are used to evaluate and interpret the models, highlighting their predictive power. The project emphasizes cheminformatics, leveraging molecular structure data and computational tools to support drug discovery and understand HER2-related chemical behavior.

TODO: 
1. Perform Hyperparameter tuning to increase predictive capabilities of the model.
2. Host as a webapp
