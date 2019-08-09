## August 2019


* week 04-09:
  * simulation: analyzing S0/S1.
  * isomir meta-analysis: getting new samples from other experiments

* week 01-05:
  * simulation: working on script to parse the new naming.
  * mirtop and mirgff3: working on developer team recruitment.
 
## July 2019

* week 21-26:
  * simulation: working on re-analysis monitoring resources
  * isomir meta-analysis:  running the 3 projects that use mirxplor data and re-analyze with bowtie
* week 14-19:
  * mirtop and mirgff3: convert to Bioinformatics format and re-submit
  * simulation: starting re-analysis monitoring resources
  * isomir meta-analysis: cleaning mirxplor references to contain sequences with H distance of 5 or more
* week 7-12:
  * mirtop and mirgff3: final revisions and adapting the code and repository files to 1.2 version
  * simulation: continueing with S4 and S5 rounds re-analysis
* week 1-5:
  * mirtop and mirgff3: revision of mirtop paper. Create new 1.2 version of format to add new headers. Optional genomic coordinates as output.
  * simulation:  continueing with S2 and S3 rounds re-analysis
  * isomir meta-analysis: get all samples trimmed by bcbio

## June 2019

* week 24-28:
  * isomir meta-analysis: create a new repository for the analysis, get all the samples trimmed for the next step
  * simulation: move back to original cluster to normalize analysis and calculate resources
* week 16-21:
  * isomir meta-analysis: starting getting data from last smrna kit comparison
  * simulation: creating new environment in new computer system and re-analyze new dataset
* week 3-7: 
  * simulation: discussion about repeat all in a machine, add bwa + mirtop, add S0
  * mirgff3_viz: discussion how to add deseq2 to the app
  * isomir meta-analysis: touch bases with Ioannis to see next step of synthetic

## May 2019

* week 28-31: remove nonindels from simulated bam files.
* week 20-24: complete simulation figures. Fix mirtop issue.
* week 13-17: adding more tools to the simulation layers. Debug mirgff3_shiny to accept big files.
* week 5-10: automatizing simulator analysis. adding color options to mirgff3-shiny.
* week 29Apr-2May: working on round 3 and round 4 of simulator project. First draft for Rshiny app to visualize isomiRs.

## April 2019

* week 21-26: finishing tier2 of simulator analysis.
* week 15-19: running tier2 of simulation project.
* week 1-5: fix issue in mirtop affecting sequences that map in the same precursor, different positions. work on more figure to show difference between synthetic and biological samples.

## March 2019

* week 25-29: preseting mirtop to BIMDC institute. Working on figure for all the data analyzed until now.
* week 18-22: resubmitting mirtop/mirgff3 paper and debuging scripts from simulation project.
* week 11-15: working on isomir accuracy project to present to Bioinformatics club. Fixing some issues in mirtop API suit.
* week 4-8: work on tewari commonality for equimolar data. Starting visualization tool that uses GFF3 format.

## February 2019

* week 25-1: work on optimir compatibility and sqlite method to analyze big files.
* week 18-22: improving mirtop to handle Manatee, exploring to work with sqlite instead of dicts.
* week 11-15: improving mirtop to handle big bam with genomic positions. Start discussion about in person mirtop meeting.
* week 4-8: adding new memebers. Supporting chunk files for seqbuster. Script to parse big gff3 files for simulator project.

## January 2019

* week 28-1: adapt mirtop to read in chunk BAM files from precursor hits
* week 21-25: start the draft to put all the meta-analysis together in a google docs
* week 14-18: communication with Illumina to figure out a plan to sequence synthetic samples
* week 21-25: working on script to design unique synthetic sequences

## December 2018

* week 10-15: working on paper tables and merging suggestion from authors.
* week 2-7: talk at BIG meeting in Boston. https://bluejeans.com/s/h4CR2.

## November 2018

* week 25-30: working on mirtop paper and preparing format to final review round. 
* week 12-16: design experiment for checking truncation events.
* week 5-9: add new data set to the analysis, maybe not possible to share right now.
* week 29-2: more modification to the mirGFF3 to addition variants. Finishing paper figure.

## October 2018

* week 22-26: Analyze Van Dijk data with spikeins to compare with current data. Update mirGFF3 definition for version 1.1.
* week 15-19: Add mirge2.0 and custom tewari synthetic plots to equimolar analysis. Discussion about changing some ideas of the mirgff3 format.
* week 8-12: Add gff3 to fasta. Analyze custom synthetic data from tewari set. Synthetic data analyzed by mirge2.0.
* week 1-5: Sync the version of mirGFF3, mirtop revision paper. Comparing plasma vs equimolar: https://github.com/miRTop/incubator/blob/master/projects/tewari_equimolar/plasma_vs_equimolar.md.

## September 2018

* week 24-28: New plots for the equimolar analysis to show the imporance of isomiRs found in the synthetic data.
* week 17-21: Working on equimolar analysis to define the background noise. (https://github.com/miRTop/incubator/blob/master/projects/tewari_equimolar/commonality.md)
* week 10-14: Studying the random isomiR generation in synthetic data.
* week 4-7: Support GFF3 from external tools that don't have UID specified.

## August 2018

* week 27-31: working on figure to show the commonality among labs and replicates at the same time.
* week 20-24: vacation time.
* week 13-17: working on testing IDR as a possible metric for reproducibility.
* week 6-10: first online meeting and plan for tewari re-analysis next steps. Starting the first draft for mirtop paper.

## July 2018

* week 30-2: improving log in stats command to be compatible with multiqc
* week 16-20: discussing road map for 1/2 2018
* week 9-13: adding compatibility with python 3

## June 2018

* week 25-29: Documenting functions in devel branch.
* week 17-22: Improving figure formats for tewari analysis.
* week 11-14: Generating [replicates reproducibility figures]l(https://github.com/miRTop/incubator/tree/master/projects/tewari)
* week 4-8: Generating [stats figures for each too]l(https://github.com/miRTop/incubator/tree/master/projects/tewari#for-each-tool-similarity-between-replicates-of-each-labprotocol)

## May 2018

* week 28-1:Fixing sRNAbench importer code.
* week 19-25: Working on commonality figures for bcbio and miRge for tewari data.
* week 11-16: Fixing bugs when joining miRge GFF into one file
* week 7-8: Running tewari data with sRNAbench, PROST and isomirSEA, preparing scripts for general stats for bcbio and miRge for pilot samples.
* week 1-4: Sharing trimmed data. Fixing --add-extra for isomiR-SEA tool

## April 2018

* week 23-27: Running data through bcbio to get trimmed data. Add extra attribute with Variants and nucleotides to allow better visual inspection.
* week 9-13: Fixing bugs in merge and stats thanks to @AlisR.
* week 2-6: Integrating PROST! output and updating synthetic data analysis.

## March 2018

* week 26-30: Working on [benchmarking report](https://github.com/miRTop/incubator/tree/master/synthetic)
* week 19-24: Adapting new sRNAbench format and discussion about PROST output
* week 12-16: Working on [abstract](https://github.com/miRTop/miRTOP.github.io/blob/master/docs/bosc2018_lpantano.pdf) for [BOSC2018](https://gccbosc2018.sched.com) presented by Lorena Pantano
* Week 5-9: Integrating [PROST tools](https://github.com/uoregon-postlethwait/prost) into miRTop command line

## February 2018

* Add summary function to miRTop
* Compatibility with isomiR-SEA

## January 2018

* Analyzing synthetic data to debug tools output
