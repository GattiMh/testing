# Coding example for interview

To run the notebook you will need different packages. 
Thankfully most of them are avaliable from the [https://github.com/volkamerlab/teachopencadd] repository.
Make sure to install based on your operative system. The notebook was originally tested on M1 Macs.

If you want to use Chemplot funcionalities, make sure to install it as well [https://github.com/mcsorkun/ChemPlot].


All the above packages can be easily installed via conda or mamba. Is it advisable to create a new enviroment as well. Creating an enviroment from teachopencadd is enough.


Notebook will extract data from ChEMBL using TeachOpenCadd template notebook, then apply physchem filters. Finally Random Forest Regressor and SVM will be used on the retrieved set.
