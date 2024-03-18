# Repeat-based-holocentromeres-of-Luzula-sylvatica
This repository contains the code used for analysis in the "Repeat-based holocentromeres of *Luzula sylvatica* (Juncaceae) reveal new insights into the evolutionary transition to holocentricity" article.

Input data files for executing the code are available upon request.

<img src=https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/IMG-20230703-WA0000%20(1).jpg width="100" title="photo: Stefan Steckenborn"/>

# Contents of the notebooks/ folder:
## ChIP-seq analysis

[**chip_seq_peak_calling**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/chip_seq_peak_calling.ipynb) - mapping reads, peak calling, replicate merging

[**merging_distance_optimization**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/merging_distance_optimization.ipynb) - calculating silhouette score, sum of squares for a range of merging distances

[**epigenetic_mark_enrichment**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/pigenetic_mark_enrichment.ipynb) - create bigwig files showing regions enriched for epigenetic marks from bam files, replicate merging, create metaplots showing enrichment of genomic elements 

[**colocalization_simulated**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/colocalization_simulated.ipynb) - analyze overlaps between genomic and epigenomic features using Monte Carlo simulations, create heatmap with percentiles

## Centromeric units analysis
[**centromeric_units**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/centromeric_units.ipynb) - calculate size, density, count of CENH3 units

[**functional_centromeric_arrays**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/functional_centromeric_arrays.ipynb) - identify overlaps of CENH3 units with satellites, visualize their size, extract their sequences, create dotplots


[**moddotplot_stats**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/moddotplot_stats.ipynb) - calculate average similarities in functional vs nonfunctional arrays

[**array_nonB_structures**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/array_nonB_structures.ipynb) - identify dyad symmetries, visualize them

[**colocalization_correlogram**](https://github.com/437364/Repeat-based-holocentromeres-of-Luzula-sylvatica/blob/main/notebooks/colocalization_correlogram.ipynb) - create correlogram from bed files
