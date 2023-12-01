# Repeat-based-holocentromeres-of-Luzula-sylvatica
This repository contains the code used for analysis in the "Repeat-based holocentromeres of Luzula sylvatica (Juncaceae) reveal new insights into the evolutionary transition to holocentricity" article



# Contents of the notebooks/ folder:
## ChIP-seq analysis

**chip_seq_peak_calling** - mapping reads, peak calling, replicate merging

**merging_distance_optimization** - calculating silhouette score, sum of squares for a range of merging distances

**epigenetic_mark_enrichment** - create bigwig files showing regions enriched for epigenetic marks from bam files, replicate merging, create metaplots showing enrichment of genomic elements 

## Centromeric units analysis
**centromeric_units** - calculate size, density, count of CENH3 units

**functional_centromeric_arrays** - identify overlaps of CENH3 units with satellites, visualize their size, extract their sequences, create dotplots


**modddotplot_stats** - calculate average similarities in functional vs nonfunctional arrays

**array_nonB_structures** - identify dyad symmetries, visualize them
