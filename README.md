
# Mirtop

## project for small RNA standard annotations

## [<span aria-hidden="true" class="octicon octicon-link"></span>](#mirna-transcriptomic-open-project-mirtop)miRNA-Transcriptomic Open Project (miRTOP)

Citation: [![10.5281/zenodo.45385](https://zenodo.org/badge/doi/10.5281/zenodo.45385.svg)](http://dx.doi.org/10.5281/zenodo.45385)

[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)  
<iframe src="https://calendar.google.com/calendar/embed?src=h75473qidg12g8md605lsrcu0g%40group.calendar.google.com&amp;ctz=America%2FNew_York" style="border: 0" scrolling="no" width="600" height="300" frameborder="0"></iframe>

### Goal

The main goal of this project is to create a reflection group on metazoan [microRNAs (miRNAs)](https://en.wikipedia.org/wiki/MicroRNA), open to all interested researchers, to identify blockages and develop standards and guidelines to improve miRNA research, resources and communication. This can go through the use of standardized file formats, gene and variants nomenclature guidelines, and advancements in miRNA biology understanding. The group will eventually also aim at expanding its breadth to the development of novel tools, data resources, and best-practices guidelines to benefit the scientific community by providing high confidence validated research and analysis strategies, regardless the expertise in this field.

Read [Road trip 2018](https://github.com/miRTop/miRTOP.github.io/blob/master/docs/road_trip_2017.md)

### Why

The motivation and emergence of this group came from the simultaneous publication of two articles from two independent groups and addressing the question of miRNA diversity, origins, evolution, and annotation:

*   Desvignes, T., Batzel, P., Berezikov, E., Eilbeck, K., Eppig, J. T., McAndrews, M. S., Singer, A., Postlethwait, J. H. (2015). miRNA Nomenclature: A View Incorporating Genetic Origins, Biosynthetic Pathways, and Sequence Variants. Trends in Genetics : TIG, 31(11), 613–626\. [http://doi.org/10.1016/j.tig.2015.09.002](http://doi.org/10.1016/j.tig.2015.09.002)
*   Fromm, B., Billipp, T., Peck, L. E., Johansen, M., Tarver, J. E., King, B. L., Newcomb J., Sempere L. F., Flatmark K., Hovig E., Peterson, K. J. (2015). A Uniform System for the Annotation of Vertebrate microRNA Genes and the Evolution of the Human microRNAome. Annual Review of Genetics. [http://doi.org/10.1146/annurev-genet-120213-092023](http://doi.org/10.1146/annurev-genet-120213-092023) ([http://mirgenedb.org](http://mirgenedb.org))

In addition, plants miRNA research is facing the same problems. The different origin of plant and metazoan miRNA systems, however, make the creation of a unified “plant & metazoan” pattern hazardous. Nevertheless, tentative standardization on specific aspects is a future goal of the group.

*   Budak, H., Bulut, R., Kantar, M., & Alptekin, B. (2015). MicroRNA nomenclature and the need for a revised naming prescription. Briefings in Functional Genomics, elv026–. [http://doi.org/10.1093/bfgp/elv026](http://doi.org/10.1093/bfgp/elv026)

### How

If you work in relation with the miRNA field, and want to take part in this reflection group, please [join us](https://github.com/miRTop/miRTOP.github.io/issues/1) and share your ideas in order to create a large community working together to improve the study and analysis of miRNA data.

The idea is to add knowledge here, where people have easily access to the most used tools, or the best way to create/use data, or what are the current challenges we face nowadays. This project won't lead to publication by itself, but it will bring together researchers working in this field, that of course can lead to collaboration, that could result in publications to be added here. The way the content will be added is by proposing a topic/paper/tool in the github issue tracker page, after discussion collaborators will decide the following steps for the proposal.

### Current projects:

See weekly [Updates](https://github.com/miRTop/miRTOP.github.io/blob/master/History.md).  

*   [miRNA GFF3 format](https://github.com/miRTop/incubator/blob/master/format/definition.md) containing data from small RNA-seq

*   [mirtop command line tool](https://github.com/miRTop/mirtop/tree/dev) to handle the GFF3 format and add usability functions to help the use of it

*   Testing the concept with [public data](https://github.com/miRTop/incubator/tree/master/tewari)

*   [miRNA simulator and tools benchmarking](https://github.com/miRTop/simulator)

If you have a new idea or project, make a proposal [at our incubator page.](https://github.com/miRTop/incubator/blob/master/README.md).

### Current discussion:

*   Establishment of a unified Nomenclature system: Two novel miRNA nomenclature systems have been simultaneously proposed by independent teams, in addition to the schemes proposed by previous groups. One focused on evolutionary conservation and clear orthology establishment to provide phylogenetically informative names based on Human annotation (Fromm and Peterson’s group), while the other envisioned a system for sequence variation analysis following nomenclature guidelines in use for coding-genes (Desvignes and Postlethwait group). The aim of this project is thus to establish a convergent framework, incorporating the strengths of each proposed system, to finalize a unified and persistent nomenclature system.

*   IsomiRs nomenclature: IsomiRs have proven to be bona fide variants of miRNA expression and could in some cases be functionally important and having different target sets than the reference miRNA they vary from. Because of functional importance of isomiRs, it appears crucial to be able to refer to a given one in a non-ambiguous way. The aim of this project is thus to formulate a standardized format for isomiR referencing and offer tools to apply them in an easy and general way.

Future projects and discussions:

*   What is the biological relevance of [moRNAs](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4607157/)? How to detect and annotate them?

### Contributors:

*   Lorena Pantano, Phd. Harvard TH Chan School of Public Health, Boston, USA
*   Thomas Desvignes, Phd. Institute of Neuroscience, University of Oregon, Eugene, OR, USA
*   John H. Postlethwait. Phd, Institute of Neuroscience, University of Oregon, Eugene, OR, USA
*   Karen EIlbeck, Phd. University of Utah, Biomedical Informatics.
*   Ioannis Vlachos, Phd. Brigham & Women's Hospital, Broad Institute of MIT and Harvard, Harvard Medical School
*   Bastian Fromm, Phd. Department of Tumor Biology. Institute for Cancer Research. Norwegian Radium Hospital. Oslo University Hospital
*   Marc K. Halushka, MD, Phd. Department of Pathology, Johns Hopkins University School of Medicine, Baltimore, MD, USA
*   Michael Hackenberg, Phd. Bioinformatics Group. University of Granada.
*   Gianvito Urgese, Phd. Politecnico di Torino, Italy
*   Milad Bastami, PhD of Medical Genetics
*   Sinan Uğur Umu PhD. Department of Research, Cancer Registry of Norway, Oslo, Norway.
*   Shruthi Bandyadka. Partners Personalized Medicine, Cambridge MA.
*   Xavier Bofill, National Cancer Institute (NCI).
*   Marc R. Friedländer5, Science for Life Laboratory, Department of Molecular Biosciences, The Wenner-Gren Institute, Stockholm University, Stockholm, Sweden.<\li>
*   Florian Thibord, Phd student. INSERM UMR_S 1219, Bordeaux Population Health Research Center, University of Bordeaux, Bordeaux, France
