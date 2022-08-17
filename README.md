# RanForrest: Novel metrics and visualizations for gene and cell-type prevalence across single-cell studies

## Dataset:
To develop and test our analysis method, we used the scRNA-seq dataset from [Intra- and Inter-cellular Rewiring of the Human Colon during Ulcerative Colitis](https://singlecell.broadinstitute.org/single_cell/study/SCP259/intra-and-inter-cellular-rewiring-of-the-human-colon-during-ulcerative-colitis). 

The authors sequenced samples from the colon mucosa of 12 healthy donors and 18 patients diagnosed with Ulceratice Colitis. This dataset provides a framework for interrogating complex human diseases and mapping risk variants to cell types and pathways.



## Experiments
### RanForrest:
In this section, we use random forest classifier to identify the cell type that has more distinguishable cells between healthy and inflamed. Further information and details are explained in RanForrest.ipynb.


### DE heatmaps:
In this section, we performed differential expression (DE) analysis using two different statitical methods (t-test and wilcoxon) on the genes of cell types we idenfied with RanForrest classifier and visuzalied DE of top 5 marker genes with heatmaps. Further information and details are explained in DE_Analysis.ipynb.


### Violin plots: 
In this section, we build a new function to visualize stacked violin plots among diffent subgroups of the chosen dataset. This function can be seen as an extension of besca's split violin plots. Further information and details are explained in Stacked Violin Plot.ipynb.



## References:
1. Smillie, C.S., Biton, M., Ordovas-Montanes, J., Sullivan, K.M., Burgin, G., Graham, D.B., Herbst, R.H., Rogel, N., Slyper, M., Waldman, J. and Sud, M., 2019. Intra-and inter-cellular rewiring of the human colon during ulcerative colitis. Cell, 178(3), pp.714-730.
2. Skinnider, M.A., Squair, J.W., Kathe, C., Anderson, M.A., Gautier, M., Matson, K.J., Milano, M., Hutson, T.H., Barraud, Q., Phillips, A.A. and Foster, L.J., 2021. Cell type prioritization in single-cell data. Nature biotechnology, 39(1), pp.30-34.
3. Squair, J.W., Skinnider, M.A., Gautier, M., Foster, L.J. and Courtine, G., 2021. Prioritization of cell types responsive to biological perturbations in single-cell data with Augur. Nature Protocols, 16(8), pp.3836-3873.
