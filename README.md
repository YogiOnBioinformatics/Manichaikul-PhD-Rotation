# Manichaikul-PhD-Rotation
University of Virginia School of Medicine (UVA SOM)

Biomedical Sciences Graduate Program (BIMS)

Computational Biology PhD Program 

Work done during 1st rotation with Professor Ani Manichaikul. 
<br>
<br>

## Files: 

📄 `./presentation/Manichaikul_Rotation_Presentation.pdf`: 

Talk given to Manichaikul group summarizing my work during this rotation. 

📓 `./qtl-association/notebooks/matching.ipynb`: 

Find exact and "fuzzy" matches between significant variants that are (e/p/m)QTL. 

Distance threshold set at 1 million. 

📓 `./rna-seq-regression/`: 

Linear Regression to model key lung function metrics based on expression levels using `MESA` participants and determining significant genes when accounting for covariates.

<b>Overall model</b>: 

```
Lung Volume Metric ~ Specific Gene Expression Level + PEER factors + Principal Components 1-11 from WGS data + Phenotypic covariates
```


📓 `./rna-seq-regression/notebooks/join_and_matrixize_data.ipynb`: 

Load heterogeneous data sources, engineer features, join matrices, output joined matrix. 


📓 `./rna-seq-regression/notebooks/regression.ipynb`:

Testing associations between key COPD-related metrics and each individual gene for each cell type using `Linear Regression`. 
