# [docker-builds](#)
This repository contains the Dockerfiles and other assorted files necessary for building Docker images for a variety of programs used by members of the StaPH-B (State Public Health Lab Bioinformatics) consortium. The purpose of this repository is to provide a centralized location for Docker images that is easily accessible for users, with clear documentation on how the containers were built and how to use them.

If you would like to contribute with a Docker image or improve upon the existing images, please fork the repository, make your changes/additions, and submit a pull request. If you are having an issue with an existing image, please submit an issue. We welcome any and all feedback!  
[See more details on how to contribute here](https://staph-b.github.io/docker-builds/contribute/)

## [Docker User Guide](https://staph-b.github.io/docker-builds/)
We have also created a user guide that outlines methods and best practices for using and developing docker containers.  
[Docker User Guide](https://staph-b.github.io/docker-builds/)

### What about Singularity?
For many people Docker is not an option, but Singularity is. Most Docker containers are compatible with Singularity and can easily be converted to Singularity format. Please see the User Guide linked above to for instructions on how to download docker images from dockerhub and how to run them using Singularity. We've worked hard to ensure that our containers are compatibile with Singularity, but if you find one that isn't, please leave an issue and let us know!

## [Available Docker images](https://hub.docker.com/r/staphb/)
[![Build Status](https://travis-ci.com/StaPH-B/docker-builds.svg?branch=master)](https://travis-ci.com/StaPH-B/docker-builds) (Build only reflects those containers that have been added to the TravisCI tests)

| Software | Version | Link |
| :--------: | ------- | -------- |
| [ABRicate](https://hub.docker.com/r/staphb/abricate/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/abricate.svg?style=popout)](https://hub.docker.com/r/staphb/abricate) | <ul><li>0.8.7</li><li>0.8.13</li><li>0.8.13s (+serotypefinder db)</li><li>0.9.8</li><li>1.0.0</li></ul> | https://github.com/tseemann/abricate |
| [ARIBA](https://hub.docker.com/r/staphb/ariba/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/ariba.svg?style=popout)](https://hub.docker.com/r/staphb/ariba) | <ul><li>2.14.4</li></ul> | https://github.com/sanger-pathogens/ariba |
| [Augur](https://github.com/nextstrain/augur) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/augur.svg?style=popout)](https://hub.docker.com/r/staphb/augur) | <ul><li>6.3.0</li><li>7.0.2</li><li>8.0.0</li><li>9.0.0</li></ul> | https://github.com/nextstrain/augur |
| [Auspice](https://github.com/nextstrain/auspice) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/auspice.svg?style=popout)](https://hub.docker.com/r/staphb/auspice) | <ul><li>2.12.0</li></ul> | https://github.com/nextstrain/auspice |
| [BBTools](https://hub.docker.com/r/staphb/bbtools/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/bbtools.svg?style=popout)](https://hub.docker.com/r/staphb/bbtools) | <ul><li>38.76</li><li>38.86</li></ul> | https://jgi.doe.gov/data-and-tools/bbtools/ |
| [bcftools](https://hub.docker.com/r/staphb/bcftools/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/bcftools.svg?style=popout)](https://hub.docker.com/r/staphb/bcftools) | <ul><li>1.10.2</li><li>1.11</li></ul> | https://github.com/samtools/bcftools |
| [bedtools](https://hub.docker.com/r/staphb/bedtools/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/bedtools.svg?style=popout)](https://hub.docker.com/r/staphb/bedtools) | <ul><li>2.29.2</li></ul> | https://bedtools.readthedocs.io/en/latest/ |
| [BWA](https://hub.docker.com/r/staphb/bwa) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/bwa.svg?style=popout)](https://hub.docker.com/r/staphb/bwa) | <ul><li>0.7.17</li></ul> | https://github.com/lh3/bwa |
| [Canu](https://hub.docker.com/r/staphb/canu) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/canu.svg?style=popout)](https://hub.docker.com/r/staphb/canu)| <ul><li>2.0</li></ul> | https://canu.readthedocs.io/en/latest/ <BR/> https://github.com/marbl/canu |
| [Canu-Racon](https://hub.docker.com/r/staphb/canu-racon/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/canu-racon.svg?style=popout)](https://hub.docker.com/r/staphb/canu-racon) | <ul><li>1.7.1 (Canu), 1.3.1 (Racon), 2.13 (minimap2)</li><li>1.9 (Canu), 1.4.3 (Racon), 2.17 (minimap2)</li><li>1.9i (Canu), 1.4.3 (Racon), 2.17 (minimap2), (+racon_preprocess.py)</li><li>2.0 (Canu), 1.4.3 (Racon), 2.17 (minimap2)</li></ul> | https://canu.readthedocs.io/en/latest/ <br/> https://github.com/lbcb-sci/racon <br/> https://github.com/isovic/racon (ARCHIVED) <br/> https://lh3.github.io/minimap2/ |
| [centroid](https://hub.docker.com/r/staphb/centroid/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/centroid.svg?style=popout)](https://hub.docker.com/r/staphb/centroid) | <ul><li>1.0.0</li></ul> | https://github.com/stjacqrm/centroid |
| [CDC-SPN](https://hub.docker.com/r/staphb/cdc-spn/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/cdc-spn.svg?style=popout)](https://hub.docker.com/r/staphb/cdc-spn) | <ul><li>0.1 (no version)</li></ul> | https://github.com/BenJamesMetcalf/Spn_Scripts_Reference |
| [cfsan-snp-pipeline](https://hub.docker.com/r/staphb/cfsan-snp-pipeline) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/cfsan-snp-pipeline.svg?style=popout)](https://hub.docker.com/r/staphb/cfsan-snp-pipeline) | <ul><li>2.0.2</li></ul> | https://github.com/CFSAN-Biostatistics/snp-pipeline |
| [Circlator](https://hub.docker.com/r/staphb/circlator) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/circlator.svg?style=popout)](https://hub.docker.com/r/staphb/circlator) | <ul><li>1.5.6</li></ul> | https://github.com/sanger-pathogens/circlator |
| [Clustalo](https://hub.docker.com/r/staphb/clustalo) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/clustalo.svg?style=popout)](https://hub.docker.com/r/staphb/clustalo) | <ul><li>1.2.4</li></ul> | http://www.clustal.org/omega/ |
| [colorid](https://hub.docker.com/r/staphb/colorid) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/colorid.svg?style=popout)](https://hub.docker.com/r/staphb/colorid) | <ul><li>0.1.4.3</li></ul> | https://github.com/hcdenbakker/colorid |
| [cutshaw-report-env](https://hub.docker.com/r/staphb/cutshaw-report-env) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/cutshaw-report-env.svg?style=popout)](https://hub.docker.com/r/staphb/cutshaw-report-env) | <ul><li>1.0.0</li></ul> | https://github.com/VADGS/CutShaw |
| [emm-typing-tool](https://hub.docker.com/r/staphb/emm-typing-tool) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/emm-typing-tool.svg?style=popout)](https://hub.docker.com/r/staphb/emm-typing-tool) | <ul><li>0.0.1 (no version)</li></ul> | https://github.com/phe-bioinformatics/emm-typing-tool |
| [FastANI](https://hub.docker.com/r/staphb/fastani) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/fastani.svg?style=popout)](https://hub.docker.com/r/staphb/fastani) | <ul><li>1.1</li><li>1.32</li></ul> | https://github.com/ParBLiSS/FastANI |
| [FastTree](https://hub.docker.com/r/staphb/fasttree) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/fasttree.svg?style=popout)](https://hub.docker.com/r/staphb/fasttree) | <ul><li>2.1.11</li></ul> | http://www.microbesonline.org/fasttree/ |
| [FastQC](https://hub.docker.com/r/staphb/fastqc) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/fastqc.svg?style=popout)](https://hub.docker.com/r/staphb/fastqc) | <ul><li>0.11.8</li></ul> | https://www.bioinformatics.babraham.ac.uk/projects/fastqc/ <br/> https://github.com/s-andrews/FastQC |
| [Filtlong](https://hub.docker.com/r/staphb/filtlong) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/filtlong.svg?style=popout)](https://hub.docker.com/r/staphb/filtlong) | <ul><li>0.2.0</li></ul> | https://github.com/rrwick/filtlong |
| [Flye](https://hub.docker.com/r/staphb/flye) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/flye.svg?style=popout)](https://hub.docker.com/r/staphb/flye) | <ul><li>2.5</li><li>2.7</li><li>2.8</li></ul> | https://github.com/fenderglass/Flye |
| [iqtree](https://hub.docker.com/r/staphb/iqtree/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/iqtree.svg?style=popout)](https://hub.docker.com/r/staphb/iqtree) | <ul><li>1.6.7</li></ul> | http://www.iqtree.org/ |
| [iVar](https://hub.docker.com/r/staphb/ivar/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/ivar.svg?style=popout)](https://hub.docker.com/r/staphb/ivar) | <ul><li>1.1</li><li>1.1 (+ SARS-CoV2 reference)</li><li>1.2.1</li><li>1.2.1 (+ SC2 ref)</li><li>1.2.2 (+SC2 ref and artic bedfiles)</li></ul> | https://github.com/andersen-lab/ivar |
| [kma](https://hub.docker.com/r/staphb/kma/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/kma.svg?style=popout)](https://hub.docker.com/r/staphb/kma) | <ul><li>1.2.21</li></ul> | https://bitbucket.org/genomicepidemiology/kma/ |
| [Kraken](https://hub.docker.com/r/staphb/kraken/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/kraken.svg?style=popout)](https://hub.docker.com/r/staphb/kraken) | <ul><li>1.0</li><li>1.0.0_wslh_signed</li><li>1.1.1</li><li>1.1.1 (no database)</li></ul> | https://github.com/DerrickWood/kraken |
| [Kraken2](https://hub.docker.com/r/staphb/kraken2/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/kraken2.svg?style=popout)](https://hub.docker.com/r/staphb/kraken2) | <ul><li>2.0.8-beta (no database)</li><li>2.0.8-beta (MiniKraken2_v1_8GB db)</li><li>2.0.8-beta_hv (human + virus db)</li><li>2.0.9-beta (no db)</li><li>2.0.9-beta (Minikraken v2 RefSeq: bacteria, archaea, viral, and human 8GB db)</li><li>2.1.0 (no db)</li><li>2.1.1 (no db)</li></ul> | https://github.com/DerrickWood/kraken2 |
| [kSNP3](https://hub.docker.com/r/staphb/ksnp3/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/ksnp3.svg?style=popout)](https://hub.docker.com/r/staphb/ksnp3)| <ul><li>3.1</li></ul> | https://sourceforge.net/projects/ksnp/ |
| [legsta](https://hub.docker.com/r/staphb/legsta/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/legsta.svg?style=popout)](https://hub.docker.com/r/staphb/legsta)| <ul><li>0.3.7</li><li>0.5.1</li></ul> | https://github.com/tseemann/legsta |
| [Lyve-SET (includes CG-Pipeline scripts and raxml)](https://hub.docker.com/r/staphb/lyveset/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/lyveset.svg?style=popout)](https://hub.docker.com/r/staphb/lyveset) | <ul><li>1.1.4f</li><li>2.0.1</li></ul> | https://github.com/lskatz/lyve-SET https://github.com/lskatz/CG-Pipeline |
| [MAFFT](https://hub.docker.com/r/staphb/mafft/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/mafft.svg?style=popout)](https://hub.docker.com/r/staphb/mafft)  | <ul><li>7.450</li></ul> | https://mafft.cbrc.jp/alignment/software/ |
| [Mash](https://hub.docker.com/r/staphb/mash/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/mash.svg?style=popout)](https://hub.docker.com/r/staphb/mash)  | <ul><li>2.1</li><li>2.2</li></ul> | https://github.com/marbl/Mash |
| [mashtree](https://hub.docker.com/r/staphb/mashtree) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/mashtree.svg?style=popout)](https://hub.docker.com/r/staphb/mashtree) | <ul><li>0.52.0</li><li>0.57.0</li><li>1.0.4</li><li>1.2.0</li></ul> | https://github.com/lskatz/mashtree |
| [medaka](https://hub.docker.com/r/staphb/medaka) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/medaka.svg?style=popout)](https://hub.docker.com/r/staphb/medaka) | <ul><li>0.8.1</li><li>1.0.1</li><li>1.2.0</li></ul> | https://github.com/nanoporetech/medaka |
| [metaphlan](https://hub.docker.com/r/staphb/metaphlan) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/metaphlan.svg?style=popout)](https://hub.docker.com/r/staphb/metaphlan) | <ul><li>3.0.3-no-db (no database)</li><li> 3.0.3 (~3GB db) | https://github.com/biobakery/MetaPhlAn/tree/3.0 |
| [minimap2](https://hub.docker.com/r/staphb/minimap2) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/minimap2.svg?style=popout)](https://hub.docker.com/r/staphb/minimap2) | <ul><li>2.17</li></ul> | https://github.com/lh3/minimap2 |
| [mlst](https://hub.docker.com/r/staphb/mlst) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/mlst.svg?style=popout)](https://hub.docker.com/r/staphb/mlst) | <ul><li>2.16.2</li><li>2.17.6</li><li>2.19.0</li></ul> | https://github.com/tseemann/mlst |
| [Mugsy](https://hub.docker.com/r/staphb/mugsy) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/mugsy.svg?style=popout)](https://hub.docker.com/r/staphb/mugsy) | <ul><li>1r2.3</li></ul> | http://mugsy.sourceforge.net/ |
| [MultiQC](https://hub.docker.com/r/staphb/multiqc) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/multiqc.svg?style=popout)](https://hub.docker.com/r/staphb/multiqc) | <ul><li>1.7</li><li>1.8</li></ul> | https://github.com/ewels/MultiQC |
| [NanoPlot](https://hub.docker.com/r/staphb/nanoplot) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/nanoplot.svg?style=popout)](https://hub.docker.com/r/staphb/nanoplot) | <ul><li>1.27.0</li><li>1.29.0</li><li>1.30.1</li><li>1.32.0</li><li>1.33.0</li></ul> | https://github.com/wdecoster/NanoPlot |
| [NCBI AMRFinderPlus](https://hub.docker.com/r/staphb/ncbi-amrfinderplus) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/ncbi-amrfinderplus.svg?style=popout)](https://hub.docker.com/r/staphb/ncbi-amrfinderplus) | <ul><li>3.1.1b</li><li>3.8.4</li><li>3.8.28</li><li>3.9.3</li></ul> | [https://github.com/ncbi/amr](https://github.com/ncbi/amr) |
| [OrthoFinder](https://hub.docker.com/r/staphb/OrthoFinder) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/orthofinder.svg?style=popout)](https://hub.docker.com/r/staphb/orthofinder) | <ul><li>2.17</li></ul> | https://github.com/davidemms/OrthoFinder |
| [Pangolin](https://hub.docker.com/r/staphb/pangolin) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/pangolin.svg?style=popout)](https://hub.docker.com/r/staphb/pangolin) | <ul><li>1.1.14</li><li>2.0.4</li><li>2.0.5</li></ul> | https://github.com/hCoV-2019/pangolin |
| [Pilon](https://hub.docker.com/r/staphb/pilon) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/pilon.svg?style=popout)](https://hub.docker.com/r/staphb/pilon) | <ul><li>1.23.0</li></ul> | https://github.com/broadinstitute/pilon |
| [PlasmidSeeker](https://hub.docker.com/r/staphb/plasmidseeker) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/plasmidseeker.svg?style=popout)](https://hub.docker.com/r/staphb/plasmidseeker) | <ul><li>1.0</li></ul> | https://github.com/bioinfo-ut/PlasmidSeeker |
| [Prokka](https://hub.docker.com/r/staphb/prokka/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/prokka.svg?style=popout)](https://hub.docker.com/r/staphb/prokka) | <ul><li>1.13.4</li><li>1.14.0</li><li>1.14.5</li></ul> | https://github.com/tseemann/prokka |
| [QUAST](https://hub.docker.com/r/staphb/quast/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/quast.svg?style=popout)](https://hub.docker.com/r/staphb/quast) | <ul><li>5.0.0</li><li>5.0.2</li></ul> | https://github.com/ablab/quast |
| [racon](https://hub.docker.com/r/staphb/racon) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/racon.svg?style=popout)](https://hub.docker.com/r/staphb/racon)| <ul><li>1.4.3</li></ul> |  https://github.com/lbcb-sci/racon <br/> https://github.com/isovic/racon (ARCHIVED) |
| [rasusa](https://hub.docker.com/r/staphb/rasusa/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/rasusa.svg?style=popout)](https://hub.docker.com/r/staphb/rasusa) | <ul><li>0.1.0</li><li>0.2.0</li><li>0.3.0</li></ul> | https://github.com/mbhall88/rasusa |
| [RAxML](https://hub.docker.com/r/staphb/raxml/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/raxml.svg?style=popout)](https://hub.docker.com/r/staphb/raxml) | <ul><li>8.2.12 (RAxML) and 0.9.0 (RAxML Next Generation)</li></ul> | https://github.com/stamatak/standard-RAxML <br/> https://github.com/amkozlov/raxml-ng |
| [Roary](https://hub.docker.com/r/staphb/roary/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/roary.svg?style=popout)](https://hub.docker.com/r/staphb/roary) | <ul><li>3.12.0</li></ul> | https://github.com/sanger-pathogens/Roary |
| [SalmID](https://hub.docker.com/r/staphb/salmid) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/salmid.svg?style=popout)](https://hub.docker.com/r/staphb/salmid) | <ul><li>0.1.23</li></ul> | https://github.com/hcdenbakker/SalmID |
| [Samtools](https://hub.docker.com/r/staphb/samtools) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/samtools.svg?style=popout)](https://hub.docker.com/r/staphb/samtools) | <ul><li>1.9</li><li>1.10</li><li>1.11</li></ul> | https://github.com/samtools/samtools |
| [SeqSero](https://hub.docker.com/r/staphb/seqsero/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/seqsero.svg?style=popout)](https://hub.docker.com/r/staphb/seqsero) | <ul><li>1.0.1</li></ul> | https://github.com/denglab/SeqSero |
| [SeqSero2](https://hub.docker.com/r/staphb/seqsero2/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/seqsero2.svg?style=popout)](https://hub.docker.com/r/staphb/seqsero2) | <ul><li>0.1.0</li><li>1.0.0</li><li>1.0.2</li><li>1.1.0</li><li>1.1.1</li></ul> | https://github.com/denglab/SeqSero2/ |
| [seqtk](https://hub.docker.com/r/staphb/seqtk) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/seqtk.svg?style=popout)](https://hub.docker.com/r/staphb/seqtk) | <ul><li>1.3</li></ul> | https://github.com/lh3/seqtk |
| [seqyclean](https://hub.docker.com/r/staphb/seqyclean) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/seqyclean.svg?style=popout)](https://hub.docker.com/r/staphb/seqyclean) | <ul><li>1.10.09</li></ul> | https://github.com/ibest/seqyclean |
| [Seroba](https://hub.docker.com/r/staphb/seroba) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/seroba.svg?style=popout)](https://hub.docker.com/r/staphb/seroba) | <ul><li>1.0.0</li><li>1.0.2</li><li>1.0.2_wslh_signed</li></ul> | https://github.com/sanger-pathogens/seroba |
| [SerotypeFinder](https://hub.docker.com/r/staphb/serotypefinder/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/serotypefinder.svg?style=popout)](https://hub.docker.com/r/staphb/serotypefinder) | <ul><li>1.1 (I think?)</li></ul> | https://bitbucket.org/genomicepidemiology/serotypefinder/ |
| [Shovill](https://hub.docker.com/r/staphb/shovill/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/shovill.svg?style=popout)](https://hub.docker.com/r/staphb/shovill) | <ul><li>1.0.4</li><li>1.1.0</li></ul> | https://github.com/tseemann/shovill |
| [SISTR](https://hub.docker.com/r/staphb/sistr/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/sistr.svg?style=popout)](https://hub.docker.com/r/staphb/sistr) | <ul><li>1.0.2</li><li>1.1.1</li></ul> | https://github.com/phac-nml/sistr_cmd |
| [SKESA](https://hub.docker.com/r/staphb/skesa) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/skesa.svg?style=popout)](https://hub.docker.com/r/staphb/skesa) | <ul><li>2.3.0</li><li>2.4.0 (`gfa_connector` & `kmercounter` included)</li></ul> | https://github.com/ncbi/SKESA |
| [Snippy](https://hub.docker.com/r/staphb/snippy) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/snippy.svg?style=popout)](https://hub.docker.com/r/staphb/snippy) | <ul><li>4.4.5</li><li>4.5.1</li><li>4.6.0</li></ul> | https://github.com/tseemann/snippy |
| [snp-dists](https://hub.docker.com/r/staphb/snp-dists) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/snp-dists.svg?style=popout)](https://hub.docker.com/r/staphb/snp-dists) | <ul><li>0.6.2</li></ul> | https://github.com/tseemann/snp-dists |
| [SNP-sites](https://hub.docker.com/r/staphb/snp-sites) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/snp-sites.svg?style=popout)](https://hub.docker.com/r/staphb/snp-sites) | <ul><li>2.3.3</li></ul> | https://github.com/sanger-pathogens/snp-sites |
| [SPAdes](https://hub.docker.com/r/staphb/spades/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/spades.svg?style=popout)](https://hub.docker.com/r/staphb/spades) | <ul><li>3.8.2</li><li>3.12.0</li><li>3.13.0</li><li>3.14.0</li><li>3.14.1</li></ul> | https://github.com/ablab/spades </br> http://cab.spbu.ru/software/spades/ |
| [SRA-toolkit](https://hub.docker.com/r/staphb/sratoolkit/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/sratoolkit.svg?style=popout)](https://hub.docker.com/r/staphb/sratoolkit) | <ul><li>2.9.2</li></ul> | https://github.com/ncbi/sra-tools |
| [Staramr](https://hub.docker.com/r/staphb/staramr/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/staramr.svg?style=popout)](https://hub.docker.com/r/staphb/staramr) | <ul><li>0.5.1</li><li>0.7.1</li></ul> | https://github.com/phac-nml/staramr |
| [TipToft](https://hub.docker.com/r/staphb/tiptoft/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/tiptoft.svg?style=popout)](https://hub.docker.com/r/staphb/tiptoft) | <ul><li>1.0.0</li><li>1.0.2</li></ul> | https://github.com/andrewjpage/tiptoft |
| [Trimmomatic](https://hub.docker.com/r/staphb/trimmomatic/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/trimmomatic.svg?style=popout)](https://hub.docker.com/r/staphb/trimmomatic) | <ul><li>0.38</li><li>0.39</li></ul> | http://www.usadellab.org/cms/?page=trimmomatic |
| [Trycycler](https://hub.docker.com/r/staphb/trycycler/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/trycycler.svg?style=popout)](https://hub.docker.com/r/staphb/trycycler) | <ul><li>0.3.1</li><li>0.3.2</li><li>0.3.3</li></ul> | https://github.com/rrwick/Trycycler |
| [Unicycler](https://hub.docker.com/r/staphb/unicycler/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/unicycler.svg?style=popout)](https://hub.docker.com/r/staphb/unicycler) | <ul><li>0.4.7</li><li>0.4.8</li></ul> | https://github.com/rrwick/Unicycler |
| [VADR](https://hub.docker.com/r/staphb/vadr/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/vadr.svg?style=popout)](https://hub.docker.com/r/staphb/vadr) | <ul><li>1.1</li></ul> | https://github.com/nawrockie/vadr |
| [VIBRANT](https://hub.docker.com/r/staphb/vibrant/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/vibrant.svg?style=popout)](https://hub.docker.com/r/staphb/vibrant) | <ul><li>1.2.1</li></ul> | https://github.com/AnantharamanLab/VIBRANT |
| [VIGOR4](https://hub.docker.com/r/staphb/vigor4/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/vigor4.svg?style=popout)](https://hub.docker.com/r/staphb/vigor4) | <ul><li>4.1.20190131</li></ul> | https://github.com/JCVenterInstitute/VIGOR4 |
| [wtdbg2](https://hub.docker.com/r/staphb/wtdbg2/) <br/> [![docker pulls](https://img.shields.io/docker/pulls/staphb/wtdbg2.svg?style=popout)](https://hub.docker.com/r/staphb/wtdbg2) | <ul><li>2.5</li></ul> | https://github.com/ruanjue/wtdbg2 |

You can also view the list of images on Docker hub here: https://hub.docker.com/r/staphb/

## License
  * [GNU GPLv3 license](/LICENSE) was added 2020-01-16
  * We keep a list of the licenses for the main software within the docker images here: [Program_Licenses.md](/Program_Licenses.md)
  * Links to licenses for each program should also be listed as a metadata `LABEL` within each dockerfile

## Authors/Maintainers
Each Dockerfile lists the author(s)/maintainer(s) as a metadata `LABEL`, but the authors/maintainers of the docker images are:
  * [@kapsakcj](https://github.com/kapsakcj)
  * [@k-florek](https://github.com/k-florek)
  * [@garfinjm](https://github.com/garfinjm)
  * [@kevinlibuit](https://github.com/kevinlibuit)
  * [@erinyoung](https://github.com/erinyoung)
  * [@lskatz](https://github.com/lskatz)
  * [@stjacqrm](https://github.com/stjacqrm)
  * [@AbigailShockey](https://github.com/AbigailShockey)
  * [@andersgs](https://github.com/andersgs)
  * [@logan-fink](https://github.com/logan-fink)
  * [@tgallagh](https://github.com/tgallagh)
  * Kelly Oakeson
