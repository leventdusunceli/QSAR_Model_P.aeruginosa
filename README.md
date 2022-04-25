# Quantitative Structure-Activity Relationship Modelling for β-lactamase produced in *Pseudomonas aeruginosa* 

Beta-lactam antibiotics are among the most commonly used drug classes and make up 65% of the total antibiotics market [1].  Penicillins, cephalosporins and carbapenems are all classified as beta-lactam antibiotics.  This class of antibiotics have the common feature of containing a highly reactive beta-lactam ring (3-carbon 1-nitrogen ring) and act as an inhibiting agent for bacterial cell wall synthesis, consequently leading to cell death [2] [3]. 

![Untitled](https://user-images.githubusercontent.com/70526402/164441094-c93dd45b-d6b7-4f3e-ac69-0cc574012eda.png)

*Figure 1 Structure of penicillins (1) and cephalosporins (2) depicting common ß-lactam ring in red*

However, the increasing rate of resistance among different bacteria strains against ß-lactams are raising serious public health concerns.  Resistance in Streptococcus pneumoniae and Pseudomonas aeruginosa strains are particularly challenging.  Bacteria can develop various mechanisms for resistance.  Synthesis of beta-lactamase, a enzyme that breaks down ß-lactams, by pathogens are among these mechanisms [4].  **Aim of this study is to build and compare a number of QSAR models for predicting bioactivity levels of chemical compounds towards beta-lactamase synthesized particularly by Pseudomonas aeruginosa.**


Quantitative structure-activity relationship *(QSAR)* modeling is a method used in drug discovery studies for building regression or classification models using physico-chemical properties and molecular descriptors of chemical compounds [5].  The goal of QSAR models are to depict and predict the biological activity levels of chemical compounds [6].  
![16-Figure4-1](https://user-images.githubusercontent.com/70526402/164441341-26d19eda-4c4f-4bd3-9702-f461f04a8704.png)


For model building, the matrix of features consisted of chemical fingerprints and molecular descriptors of previously identified chemical compounds.  The dependent variable was pIC50 values of those chemical compounds.
Chemical fingerprints and molecular descriptor values were calculated from the SMILES notation of compounds, which were imported from the ChEMBL database.  pIC50 values were calculated from the bioactivity level information of compounds imported from the ChEMBL database. [ChEMBL search tool](https://github.com/leventdusunceli/Chembl_search) in my GitHub profile was used to import information from the ChEMBL database. 

Workflow of the project is as follows: 
1.	Importing bioactivity data from ChEMBL database 
2.	Calculate molecular descriptor values 
3.	Compute moleculr fingerprints using PaDEL software
4.	Build and evaluate regression models


**References**

*[1] 	B. Thakuria ve K. Lahon, «The Beta Lactam Antibiotics as an Empirical Therapy in a Developing Country: An Update on Their Current Status and Recommendations to Counter the Resistance against Them.,» Journal of clinical and diagnostic research : JCDR,, p. 1207–1214, 2013.* 

*[2] 	N. Pandey ve M. Cascella, Beta Lactam Antibiotics., StatPearls Publishing, 2022.* 

*[3] 	X. Zeng ve J. Lin, «Beta-lactamase induction and cell wall metabolism in Gram-negative bacteria,» Frontiers in Microbiology, cilt 4, 2013. *

*[4] 	M. Ibrahim, M. Abbas, A. Al-Shahrai ve B. Elamin, «Phenotypic Characterization and Antibiotic Resistance Patterns of Extended-Spectrum β-Lactamase- and AmpC β-Lactamase-Producing Gram-Negative Bacteria in a Referral Hospital,» Can J Infect Dis Med Microbiol., 2019.* 

*[5] 	R. Todeschini ve V. Consonni, Molecular Descriptors for Chemoinformatics, Wiley, 2009.* 

*[6] 	K. Roy, S. Kar ve R. Das, «What is QSAR? Definitions and Formulism,» %1 içinde A primer on QSAR/QSPR modeling: Fundamental Concepts., New York, Springer-Verlag Inc., 2015, pp. 2-6.*



