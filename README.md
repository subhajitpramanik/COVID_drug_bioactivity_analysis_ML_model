# COVID_drug_bioactivity_analysis_ML_model
Bioactivity analysis machine learning model for potential COVID drug molecules
For this project, we were asked to use and experiment with the drug dataset available at Chembl site, and to explore how to use different machine learning algorithm in a project and find pattern in data.
We were expected gain insights and experience in data cleaning and processing using common data-mining and machine learning library.
We were expected to submit a report about the dataset and different algorithms that were used.
During the project the use of neural network or deep learning techniques were restricted.
This is the report on the data and the techniques used in the project with interpretations.
Use Google Colab to run the file. 
Program collects data directly from Chembl Database at the runtime.

In this project our team worked on Chembl drug data, we selected the compounds that target SARS coronavirus having type – single protein from the database.

The bioactivity of the data we are calculating potency of the drug that’s the amount required to produce an effect of given intensity lower the value the more the potency.

We calculated the descriptors and fingerprint for the compounds imported and then ran different regression models to compute the bioactivity of the compounds 

CONCLUSIONS:

•	The PaDel fingerprint calculations were faster and better for predicting the bioactivity values as compared to Mordred descriptors.

•	After running and observing different models to fit the data the decision tree regressor was better in most of the iterations for Mordred data.

•	After running and observing different models to fit the data the voting regressor was better in most of the iterations for PaDEL data.

•	The max r2 achieved for Mordred data was: 0.395

•	The max r2 achieved for PaDEL data was: 0.642 (** The values of r2 can change at the time of run.)

Team Members:

1) Subhajit Pramanik - Dept. of Economic Sciences, IISER Bhopal

2) Anushk Naval - Dept. of Earth and Environmental Science, IISER Bhopal

3) Subhojit Pal - Dept. of Physics, IISER Bhopal

