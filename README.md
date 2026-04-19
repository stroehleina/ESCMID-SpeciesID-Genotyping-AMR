# ESCMID 17.04.2026 - Species determination, genotyping and AMR prediction - A gentle introduction to bioinformatics for microbial genomics

This is a companion repository to the presentation 

**Species determination, genotyping and AMR prediction - A gentle introduction to bioinformatics for microbial genomics**

held by Andreas Stroehlein at the _36th Congress of the European Society of Clinical Microbiology and Infectious Diseases_ ([ESCMID Global 2026](https://www.escmid.org/)) 
as part of an _Educational Session_ on 17th April 2026 in Munich, Germany.

This repository should serve as a (non-exhaustive) resource listing tools, publications and databases used for species determination, genotyping and AMR prediction based on whole-genome sequencing (WGS) data.
PRs are welcome.

## Species determination

### ANI/MinHash tools
- [`MASH`](https://github.com/marbl/Mash) ([MASH Paper](http://doi.org/10.1186/s13059-016-0997-x), [MASH Screen Paper](doi.org/10.1186/s13059-019-1841-x))
- [`fastANI`](https://github.com/ParBLiSS/FastANI) ([Paper](https://doi.org/10.1038/s41467-018-07641-9), [Rebuttal Paper](https://doi.org/10.1038/s41467-018-07641-9), [Reply Paper](https://doi.org/10.1038/s41467-021-24128-2))
- [`sourmash`](https://github.com/sourmash-bio/sourmash) ([Paper](https://doi.org/10.21105/joss.06830)) 
- [`pyANI-plus`](https://github.com/pyani-plus/pyani-plus) ([Paper](https://doi.org/10.1039/C5AY02550H))
- [`skani`](https://github.com/bluenote-1577/skani) ([Paper](https://doi.org/10.1038/s41592-023-02018-3))

### Taxonomy tools
- [`TakonKit`](https://bioinf.shenwei.me/taxonkit/) ([Paper](https://doi.org/10.1016/j.jgg.2021.03.006))
- [`taxonomy-tools`](https://github.com/pmenzel/taxonomy-tools)
- [`GTDB-Tk`](https://github.com/ecogenomics/gtdbtk) ([Paper](https://doi.org/10.1093/bioinformatics/btac672))

### Kraken/k-mer-based classification
- [`Kraken2`](https://github.com/DerrickWood/kraken2) ([Paper](https://doi.org/10.1186/s13059-019-1891-0))
- [`KrakenTools`](https://github.com/jenniferlu717/KrakenTools) ([Paper](https://doi.org/10.1038/s41596-022-00738-y))
- [`Kraken` databases/indices](https://benlangmead.github.io/aws-indexes/k2)

### Databases
- [Genome Taxonomy Database (GTDB)](https://gtdb.ecogenomic.org/) ([Paper](https://doi.org/10.1038/s41587-020-0501-8), [Update Paper](https://doi.org/10.1093/nar/gkab776))
- [NCBI Taxonomy](https://www.ncbi.nlm.nih.gov/taxonomy) ([FTP for downloads](https://ftp.ncbi.nih.gov/pub/taxonomy/))
- [AllTheBacteria](https://allthebacteria.org/) ([Preprint](https://doi.org/10.1101/2024.03.08.584059))
- [Type (Strain) Genome Server (DMSZ)](https://tygs.dsmz.de/)

### Ribosomal MLST (rMLST)
- [Database](https://pubmlst.org/species-id) ([Paper](https://doi.org/10.1099/mic.0.055459-0))

## Genotyping

### Species-specific geno-(sero)-typing tools

#### _Salmonella_

- [`SISTR`](https://github.com/phac-nml/sistr_cmd) ([Tool Paper](https://doi.org/10.1371/journal.pone.0147101), [Assessment Paper](https://doi.org/10.1099/mgen.0.000151))
- [`SeqSero2S`](https://github.com/denglab/SeqSero2) ([Paper](https://doi.org/10.1128/AEM.01746-19), [Update Paper (SeqSero2S)](https://doi.org/10.1128/aem.02600-24))
- [`Genotyphi` (_S._ Typhi typer)](https://github.com/typhoidgenomics/genotyphi) ([Paper](https://doi.org/10.1093/infdis/jiab414))
- [`roughy` (LPS-rough sub-typing)](https://gitlab.com/bfr_bioinformatics/roughy)

#### _Listeria_

- [`LisSero`](https://github.com/MDU-PHL/LisSero)

#### _E. coli_

- [`ECTyper`](https://github.com/phac-nml/ecoli_serotyping) ([Paper](https://doi.org/10.1099/mgen.0.000728))
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
- [`MiST`](https://github.com/BioinformaticsPlatformWIV-ISP/MiST) (can also do cgMLST; [Paper](http://doi.org/10.1186/s12864-025-12324-z))

#### Databases
- [PubMLST](https://pubmlst.org/mlst) ([Paper](https://doi.org/10.12688/wellcomeopenres.14826.1))
- [BIGSdb-Pasteur](https://bigsdb.pasteur.fr/)

### cgMLST/wgMLST

#### Tools
- [`chewBBACA`](https://github.com/B-UMMI/chewBBACA) ([Documentation](https://chewbbaca.readthedocs.io/en/latest/user/getting_started/overview.html), [Original Paper](https://doi.org/10.1099/mgen.0.000166), [ChewBBACA 3 Paper](https://doi.org/10.1186/s13073-026-01625-x))
- [`chewieSnake`](https://gitlab.com/bfr_bioinformatics/chewieSnake) ([Paper](https://doi.org/10.3389/fmicb.2021.649517))


#### Databases

- [PubMLST](https://pubmlst.org/) ([Paper](https://doi.org/10.12688/wellcomeopenres.14826.1))
- [ChewieNS cgMLST nomenclature server](https://chewbbaca.online/) ([Code](https://github.com/B-UMMI/Chewie-NS), [Paper](https://doi.org/10.1093/nar/gkaa889))
- [BIGSdb-Pasteur](https://bigsdb.pasteur.fr/)
- [Enterobase](https://enterobase.warwick.ac.uk/) ([User Guide](https://doi.org/10.1101/gr.251678.119), [Paper](https://doi.org/10.1093/nar/gkae902))

## AMR prediction/detection

- [`ABRicate`](https://github.com/tseemann/ABRICATE)
- [`AMRFinderPlus`](https://github.com/ncbi/amr) ([Paper](https://doi.org/10.1038/s41598-021-91456-0), [Documentation](https://www.ncbi.nlm.nih.gov/pathogens/antimicrobial-resistance/AMRFinder/))
- [`ResFinder`](https://github.com/genomicepidemiology/resfinder) ([Paper](https://doi.org/10.1093/jac/dkaa345))
- [`ARIBA`](https://github.com/sanger-pathogens/ariba) ([Paper](https://doi.org/10.1099/mgen.0.000131))
- [`SRST2`](https://github.com/katholt/srst2) ([Paper](https://doi.org/10.1186/s13073-014-0090-6))
- [`STARAMR`](https://github.com/phac-nml/staramr) ([Paper](https://doi.org/10.3390/microorganisms10020292))
- [`AMR++`](https://github.com/Microbial-Ecology-Group/AMRplusplus) ([Paper](https://doi.org/10.1093/nar/gkac1047))
- [`Mykrobe`](https://github.com/Mykrobe-tools/mykrobe)
- [`PointFinder`](https://bitbucket.org/genomicepidemiology/pointfinder/src/master/) ([Paper](https://pubmed.ncbi.nlm.nih.gov/29091202/))
- [`tbtAMR` (_M. tuberculosis_)](https://github.com/MDU-PHL/tbtamr) ([Paper](https://doi.org/10.1016/j.landig.2025.100939))

### Databases
- [Pathogen Detection Reference Gene Catalog](https://www.ncbi.nlm.nih.gov/pathogens/refgene/)
- [Comprehensive Antimicrobial Resistance Database (CARD)](https://card.mcmaster.ca/) ([Paper](https://doi.org/10.1093/nar/gkac920))

### Harmonization, standardization, certification
- [`abriTAMR`](https://github.com/MDU-PHL/abritamr) ([Paper](https://doi.org/10.1038/s41467-022-35713-4))
- [hAMRonization](https://github.com/pha4ge/hAMRonization) ([Preprint](https://doi.org/10.1101/2024.03.07.583950))
- [AMRRules](https://github.com/katholt/AMRrules)

## End-to-end microbial genomics pipelines, online tools and platforms (examples)
- [`Bohra`](https://github.com/MDU-PHL/bohra)
- [`AQUAMIS`](https://gitlab.com/bfr_bioinformatics/AQUAMIS) ([Paper](https://doi.org/10.3390/genes12050644))/[`MiLonga`](https://gitlab.com/bfr_bioinformatics/milonga), [`BakCharak`](https://gitlab.com/bfr_bioinformatics/bakcharak) and [`chewieSnake`](https://gitlab.com/bfr_bioinformatics/chewieSnake) ([Paper](https://doi.org/10.3389/fmicb.2021.649517))
- [GMS JASEN](https://github.com/genomic-medicine-sweden/jasen)
- [BACTOPIA](https://bactopia.github.io/v3.0.0/)
- [`AnoBac`](https://github.com/rki-mf1/anobac)
- [NCBI Pathogen Detection](https://www.ncbi.nlm.nih.gov/pathogens/) ([Documentation](https://www.ncbi.nlm.nih.gov/pathogens/pathogens_help/))
- [PathogenWatch](https://next.pathogen.watch/en)
- [Center for Genomic Epidemiology (@DTU Denmark) online bioinformatics tools](https://genepi.dk/)

## Other resources and communities

- [µBinfie Slack](http://microbial-bioinfo.slack.com/) (great community for getting help!)
- [µBinfie Podcast](https://microbinfie.github.io/)

