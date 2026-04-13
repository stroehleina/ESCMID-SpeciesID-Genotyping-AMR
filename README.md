# ESCMID 17.04.2026 - Species determination, genotyping and AMR prediction - A gentle introduction to bioinformatics for microbial genomics

This is a companion repository to the presentation 

"Species determination, genotyping and AMR prediction - A gentle introduction to bioinformatics for microbial genomics"

held by Andreas Stroehlein at the 36th Congress of the European Society of Clinical Microbiology and Infectious Diseases ([ESCMID](https://www.escmid.org/)) 
as part of an Educational Session on 17th April 2026, Munich, Germany.

This repository should serve as a (non-exhaustive) resource listing tools, publications and databases used for species determination, genotyping and AMR prediction based on whole-genome sequencing (WGS) data.

## Species determination

- [`MASH`](https://github.com/marbl/Mash) ([MASH Paper](http://doi.org/10.1186/s13059-016-0997-x), [MASH Screen Paper](doi.org/10.1186/s13059-019-1841-x))  
- [`fastANI`](https://github.com/ParBLiSS/FastANI)  
- [`sourmash`](https://github.com/sourmash-bio/sourmash)  
- [`pyANI-plus`](https://github.com/pyani-plus/pyani-plus)  
- [`skani`](https://github.com/bluenote-1577/skani)  
- [`TakonKit`](https://bioinf.shenwei.me/taxonkit/) ([Paper](https://doi.org/10.1016/j.jgg.2021.03.006))  
- [`taxonomy-tools`](https://github.com/pmenzel/taxonomy-tools)  
- [`Kraken2`](https://github.com/DerrickWood/kraken2)  
- [`KrakenTools`](https://github.com/jenniferlu717/KrakenTools) ([Paper])  
- [`Kraken` databases/indices](https://benlangmead.github.io/aws-indexes/k2)  

- [Genome Taxonomy Database (GTDB)](https://gtdb.ecogenomic.org/)  
- [NCBI Taxonomy](https://www.ncbi.nlm.nih.gov/taxonomy) ([FTP for downloads](https://ftp.ncbi.nih.gov/pub/taxonomy/))  
- [AllTheBacteria](https://allthebacteria.org/)  
- [Type (Strain) Genome Server (DMSZ)](https://tygs.dsmz.de/)

## Genotyping

### Species-specific geno(sero)typer

#### _Salmonella_

- [`SISTR`](https://github.com/phac-nml/sistr_cmd) (Paper)
- [`SeqSero2S`](https://github.com/denglab/SeqSero2) (Paper)
- [`roughy` (LPS-rough sub-typing)](https://gitlab.com/bfr_bioinformatics/roughy) 

#### Listeria

- [`LisSero`](https://github.com/MDU-PHL/LisSero)

#### _E. coli_

- [`ECTyper`](https://github.com/phac-nml/ecoli_serotyping)
- [`StxTyper`](https://github.com/ncbi/stxtyper)

#### _Klebsiella_

- [`Kleborate`](https://github.com/klebgenomics/Kleborate) ([Paper](https://doi.org/10.1038/s41467-021-24448-3))

#### _Neisseria gonorrhoeae_

- [`NGMASTER`](https://github.com/MDU-PHL/ngmaster) ([Paper](https://doi.org/10.1099/mgen.0.000076))

#### _Neisseria meningitidis_

- [`meningotype`](https://github.com/MDU-PHL/meningotype)

#### _Streptococcus pyogenes_

- [`emmtyper`](https://github.com/MDU-PHL/emmtyper)

### MLST

- [`mlst` (tool)](https://github.com/tseemann/mlst)
- [MLSTFinder (online tool)](https://genepi.dk/mlstfinder)
- [PubMLST](https://pubmlst.org/)
- [`MiST`](https://github.com/BioinformaticsPlatformWIV-ISP/MiST) (can also do cgMLST; [Paper](http://doi.org/10.1186/s12864-025-12324-z))

### cgMLST/wgMLST

#### Tools
- [chewBBACA]() ([Paper]())
- [chewieSnake]() ([Paper]())


#### Databases

- [PubMLST](https://pubmlst.org/)
- [ChewieNS cgMLST nomenclature server](https://chewbbaca.online/)
- [BIGSdb-Pasteur](https://bigsdb.pasteur.fr/)
- [Enterobase](https://enterobase.warwick.ac.uk/)

## AMR prediction

- [`tbtAMR` (_M. tuberculosis_)](https://github.com/MDU-PHL/tbtamr)
- [abriTAMR](https://github.com/MDU-PHL/abritamr) ([Paper]())
- ARIBA
- [`ABRicate`]()
- [`Mykrobe`](https://github.com/Mykrobe-tools/mykrobe)
- [Comprehensive Antimicrobial Resistance Database (CARD)](https://card.mcmaster.ca/) ([Paper](https://doi.org/10.1093/nar/gkac920))
- [`ResFinder`](https://github.com/genomicepidemiology/resfinder) ([Paper](https://doi.org/10.1093/jac/dkaa345))
- [`PointFinder`](https://bitbucket.org/genomicepidemiology/pointfinder/src/master/) ([Paper](https://pubmed.ncbi.nlm.nih.gov/29091202/), [Webtool]())
- [`AMRFinderPlus`(https://github.com/ncbi/amr)]([Paper](https://doi.org/10.1038/s41598-021-91456-0), [Documentation](https://www.ncbi.nlm.nih.gov/pathogens/antimicrobial-resistance/AMRFinder/))
- [Pathogen Detection Reference Gene Catalog](https://www.ncbi.nlm.nih.gov/pathogens/refgene/)
- [`STARAMR`](https://github.com/phac-nml/staramr)
- [HAMRonizer](https://github.com/pha4ge/hAMRonization)

## End-to-end microbial genomics pipelines and online tools (examples)

- [`BACTOPIA`](https://bactopia.github.io/v3.0.0/)
- [Bohra](https://github.com/MDU-PHL/bohra) ([Paper]) 
- [AQUAMIS]()/[MiLonga](), [BakCharak]() and [ChewieSnake]()

- [NCBI Pathogen Detection]()

- [GABI](https://github.com/marchoeppner/gabi) ([Paper])  
- [GARI](https://github.com/rki-mf1/GARI) ([Paper])  
- [Center for Genomic Epidemiology (@DTU, Denmark) online bioinformatics tools](https://genepi.dk/)


## Other resources and communities

[µBinfie Podcast](https://microbinfie.github.io/)

µBinfie Slack
