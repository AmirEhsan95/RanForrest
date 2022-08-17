# RanForrest: Novel metrics and visualizations for gene and cell-type prevalence across single-cell studies

## Dataset:
We used Human "Colon Ulcerative Colitis" dataset.

## Experiments
### RanForrest:
In this section, we use random forest classifier to identify the cell type that has more distinguishable cells between healthy and inflamed. Further information and details are explained in RanForrest.ipynb.


### DE heatmaps:
In this section, we performed differential expression (DE) analysis using two different statitical methods (t-test and wilcoxon) on the genes of cell types we idenfied with RanForrest classifier and visuzalied DE of top 5 marker genes with heatmaps. Further information and details are explained in DE_Analysis.ipynb.


### Violin plots: 
In this section, we build a new function to visualize stacked violin plots among diffent subgroups of the chosen dataset. This function can be seen as an extension of besca's split violin plots. Further information and details are explained in Stacked Violin Plot.ipynb.

