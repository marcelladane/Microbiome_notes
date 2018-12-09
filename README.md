# A continually expanding collection of RNA-seq tools

These notes are not intended to be comprehensive. They include notes about methods, packages and tools I am learing and/or would like to explore. For a comprehensive overview of the subject, consider [other bioinformatics resources](https://github.com/mdozmorov/blogs/tree/master/Bioinformatics). Issues with suggestions and pull requests are welcome!

# Table of content

* [Pipelines](#Pipelines)
* [Data](#data)

## Pipelines

- HUMAnN2: The HMP Unified Metabolic Analysis Network 2 - functional profiling and pathway reconstruction of metagenomes. Tiered approach: 1) Screening for known species with MetaPhlAn2; 2) mapping against pangenomes; 3) mapping against protein sequences. These mappings can help to assign metabolic and functional annotations. http://huttenhower.sph.harvard.edu/humann2
    - Franzosa, Eric A., Lauren J. McIver, Gholamali Rahnavard, Luke R. Thompson, Melanie Schirmer, George Weingart, Karen Schwarzberg Lipson, et al. “Species-Level Functional Profiling of Metagenomes and Metatranscriptomes.” Nature Methods 15, no. 11 (November 2018): 962–68. https://doi.org/10.1038/s41592-018-0176-y.

- Microbiome Helper - wrapper scripts and tutorials for metagenomics analysis. https://github.com/LangilleLab/microbiome_helper/wiki.
    - Comeau, André M., Gavin M. Douglas, and Morgan G. I. Langille. “Microbiome Helper: A Custom and Streamlined Workflow for Microbiome Research.” Edited by Jonathan Eisen. MSystems 2, no. 1 (February 28, 2017). https://doi.org/10.1128/mSystems.00127-16.

- phyloseq R package for import of the most OTU clustering data formats, preprocessing (normalization, standartization, subsampling, filtering), visualization (various definitions of distance, dimensionality reduction methods), and analysis (comparative) of microbiome data. phyloseq-class with four components (otu_table, sample_data, tax_table, phy_tree). Plotting functions using ggplot2 graphics. http://www.bioconductor.org/packages/release/bioc/html/phyloseq.html, http://joey711.github.io/phyloseq/, https://github.com/joey711/phyloseq
    - McMurdie, Paul J., and Susan Holmes. “Phyloseq: An R Package for Reproducible Interactive Analysis and Graphics of Microbiome Census Data.” Edited by Michael Watson. PLoS ONE 8, no. 4 (April 22, 2013): e61217. https://doi.org/10.1371/journal.pone.0061217.

 

## Data

- Database for Preterm Birth Research. Other databases - dbPTB, GEneSTATION. Different studies. Predominantly microbiome, but also CyTOF, RNA-Seq, cell-free DNA and RNA sequencing, and genotyping. Open access. http://www.immport.org/resources/mod
    - Sirota, Marina, Cristel G. Thomas, Rebecca Liu, Maya Zuhl, Payal Banerjee, Ronald J. Wong, Cecele C. Quaintance, et al. “Enabling Precision Medicine in Neonatology, an Integrated Repository for Preterm Birth Research.” Scientific Data 5 (November 6, 2018): 180219. https://doi.org/10.1038/sdata.2018.219. 

- LogMIPE study (Landscape of gut Microbiome - Pan-India Exploration) - FASTQ files from 1004 subjects from 14 geographical locations. Data, https://www.ebi.ac.uk/ena/data/view/PRJEB25642, and scripts for processing them using QIIME or Mothur pipelines, https://github.com/anirbanbhaduri/LogMPIE
    - Dubey, Ashok Kumar, Niyati Uppadhyaya, Pravin Nilawe, Neeraj Chauhan, Santosh Kumar, Urmila Anurag Gupta, and Anirban Bhaduri. “LogMPIE, Pan-India Profiling of the Human Gut Microbiome Using 16S RRNA Sequencing.” Scientific Data 5 (October 30, 2018): 180232. https://doi.org/10.1038/sdata.2018.232.


# Local files and folders

- `LogMPIE` - Microbiome Processing Pipeline, Python scripts for running Mothur, QIIME. https://github.com/anirbanbhaduri/LogMPIE

