# Figures: Genomic Baseline of AMR in Wild Baboons

This directory contains the primary and supplementary visualizations generated for the manuscript detailing the antimicrobial resistance (AMR) landscape, virulence factors, plasmids, and ecological context of the gut microbiome in wild baboons from Amboseli, Kenya. 

The figures enclosed illustrate the stark contrast between the generally low baseline AMR burden in the wild population and the localized complexity found within unbinned contigs and a single multidrug-resistant (MDR) hyper-carrier.

## Main Figures

* **Figure 1: MAG Quality and ARG Overview** Summary of Metagenome-Assembled Genomes (MAGs) quality based on MIMAG guidelines (CheckM2). Includes a completeness vs. contamination scatter plot and an overview of ARGs detected across 724 dereplicated high- and medium-quality MAGs using ABRicate/CARD.
* **Figure 2: ARG Distribution (MAGs vs. Unbinned Contigs)**
  Detailed overview of ARG carriage, including heatmaps for reconstructed MAGs and unbinned contigs. Highlights temporal detection across sampling dates and specifically isolates the elevated ARG carriage in a multidrug-resistant (MDR) outlier individual.
* **Figure 3: Phylogeny and Ecological Context of *E. coli***
  Maximum likelihood phylogenetic tree of *E. coli* MAGs compared to public references, alongside Clermont phylogroup assignments. Includes a spatial distribution map of the sampled social group (Vogue), the MDR outlier (Viyela), and shared local water sources during May 2014.
* **Figure 4: Virulence Factors and Plasmid Identification**
  Comparative distribution of virulence-related functional categories between high-quality MAGs and unbinned contigs. Features a clustered heatmap of specific virulence factors across representative MAGs and mobility/host-range profiles of plasmids identified via PlasmidFinder.
* **Figure 5: Novel ARGs via Deep Learning**
  Comparison of unique and overlapping ARGs identified by ABRicate and the deep learning-based tool DeepARG. Details the prevalence of potentially novel ARGs detected exclusively by DeepARG across both MAGs and short-read datasets.

## Supplementary Figures

* **Supplementary Figure 1: Population and Sequencing Overview**
  Demographics of the baboon population, including social group distribution, host sex, and age. Also includes sequencing depth comparisons (highlighting the Viyela outlier) and the correlation between host age and ARG count per sample.
* **Supplementary Figure 2: MAG Taxonomic Assignment**
  Taxonomic composition of the reconstructed MAGs reported at both the phylum and family levels.
* **Supplementary Figure 3: Microbiome Composition of the MDR Outlier**
  Specific microbiome profiling for the Viyela stool sample, detailing the number of reconstructed MAGs per sample and microbiome composition at the family level.
* **Supplementary Figure 4: Expanded Spatial Map**
  Detailed spatial map tracking the movements of sampled social groups during May 2014 relative to the Viyela outlier and specific water holes known to be shared with livestock.
* **Supplementary Figure 5: Genomic Co-localization Maps**
  Linear gene maps of representative assembled contigs from the outlier MAG (VIY-55519), demonstrating the physical integration and close proximity of ARGs with ExPEC virulence determinants.
* **Supplementary Figure 6: ABRicate vs. DeepARG Annotations**
  Alluvial plot visualizing the relationship and flow of gene annotations between the ABRicate and DeepARG tools.

---
**Note on Reproducibility:** Raw data and intermediate tables used to generate these plots are located in the `/data/` directory, while the plotting scripts can be found in `/scripts/`.
