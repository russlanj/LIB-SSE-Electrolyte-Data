# Lithium-ion Battery (LIB) Solid State Electrolyte (SSE) Ionic Conductivity (IC) Prediction using Machine Learning

This repositry contains the following:

1.- "Collected Data (no features).xlsx" - This file contains collected materials from previous reported works regarding solid-state electrolytes.

2.- "References.xlsx" - This file contains links to references for all materials employed in the training and testing processes.

3.- "Initial Dataset + features.csv" - This file contains the initial dataset used in this work and the features generated for each material.

4.- "ICSD predictions.csv" - This file contains ionic conductivity predictions and generated features for ~30k materials found in the ICSD library.

5.- "145 Stable compounds.csv" - This file contains predicted ionic conductivity for 145 materials found in ref 14 (DOI: https://doi.org/10.1016/j.isci.2019.05.036).

6.- "Compound validation.csv" - contains the experimental ionic conductivity as well as the generated features to be predicted by our model.

7.- "Li-ion Battery Prediction.ipynb" - This file contains the code employed in this work in order to make ionic conductivity predictions in a jupyter notebook form.

8.- "Pickle model" - is a folder containing "Li-ion full model" pickle file of the full modle used, and "filtered_features" that includes the filtered features used for the model.

