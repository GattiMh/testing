# Coding example for interview

To run the notebook you will need different packages. 
Most of them can be installed using ```conda``` or ```mamba```

Packages required are:

```
mamba install rdkit
mamba install chembl_webresource_client
mamba install scikit-learn
mamba install tqdm
mamba install chemplot
```
If you are on M1 Macs (like this notebook was tested) you might want to include

```
pip install bokeh==2.4.3
```
This should help in case you want to use the interactive visualiser plot with Chemplot.
All the Chemplot code is not required to run the full pipeline, just for visualisation.

Chembl extraction pipeline was taken from the [https://github.com/volkamerlab/teachopencadd] repository.

You can read about chemplot here [https://github.com/mcsorkun/ChemPlot].

Notebook will extract data from ChEMBL using TeachOpenCadd template notebook, then apply physchem filters. Finally Random Forest Regressor and SVM will be used on the retrieved set.
Metrics will be displayed for both models. 

Feel free to change the target (currently set for ABL-1) by providing a different uniprot_ID
