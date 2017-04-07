# mirTop plan trip 2017

The milestones for this year are:  

* Propose specific topics to solve
* have a first global agreement for miRNA and isomiRs nomenclature 
* a bioinformatics tool that implements these rules. 

We expect this will be enough to get bioinformaticians adopt it since this tool can be plugged at the end of any pipeline to get to the final format.

There would be three main branches:

*	miRNA nomenclature guidelines: Authors (Thomas), help wanted
*	isomiRs nomenclature guidelines: Authors (Lorena, Thomas), help wanted
*	Tool(s): Authors (Lorena), help wanted

We encourage at least 2-3 authors per branch to ensure continuity of the project.

## Code of conduct

This group promotes inclusion and collaboration. Any hostile or disrespectful behaviors will not be accepted. We are doing this for science and for the community. Please, read the code of conduct. (http://todogroup.org/opencodeofconduct/)

## Roles

The project accepts different roles. All roles are important contributions and we encourage anyone to participate even if the available time to participate is small. Researchers can decide what role to have and can change at any time, all participations will be recorded. All researchers, independently on the role, will be included in the paper.

*	Contributors: does not require high participation but at least regular feedback on some of the milestones we need to reach
*	Developer: helping with the development of the tool
*	Author: requires to be active and make important contributions on some aspects of the project

## Keydates

* June-30-2017: First draft of isomiRs/miRNA naming
* July-23/24-2017: First version (0.99) of code implementing the naming rules. Done in CodeFest (ISMB)
* October-*-2017: Functional version of the code to be released on these days, at the same time than the smallRNA collaborative retreat event that will occur in Boston (read at the end of the document).
* December-*-2017: Draft of the paper and submission 

## Meetings

*	June-*-2017: Virtual meeting to discuss the proposed ideas
*	July-23/24-2017: Developers virtually working together during codeFest event 
*	September-*-2017: Virtual meeting to show the current state and suggest more changes if needed
*	November-*-2017: Virtual meeting to discuss whether there is problem with deadlines

After each meeting there will be some minutes summarizing all the important points and milestones.

## Bioinformatics tool:

Features of the tool (python for now, other language is welcome):

Current features:

*	Read a BAM file with reads annotated against miRBase precursos and give a tabular file. Example: https://github.com/miRTop/mirtop/blob/master/docs/output_table.md
*	Take multiple files at the same time
*	Give count matrix for miRNA and isomiRs containing all samples
*	Adapted the current rules
*	It can creates a VCF files with nucleotides substitution based on genome coordinates

To be implemented:
*	Be able to parse from genomic BAMs
*	API to create/read entries in correct format 
*	collapse samples into count matrix 
*	query files (multiple files/single file)
*	output stats about miRNAs/isomiRs
*	mapper between versions. To help people move from version to version.
*	create unique ID similar to tRNA from isidore

To show the usability of this, we can reanalyze miRBase reads and implement a web-page for visualization (HSA data is done).

## Internal communication

This project supports the openness in science. All material will be in our public GiTHub account. With some exceptions, we will handle some drafts internally until it reaches sufficient quality for publication. 

We recommend discussing issues through the GiTHub repository. That way everybody can catch up and reply whenever needed. The advantage of this method is that everybody can be aware of the updates of the project, while you still can communicate by email, and you can ping people into the conversation. You can also mute any channel if you like to be involved in only some part of the project.

## Dissemination

Any researcher involved in the project has the right to present this work in any research meeting, as a talk or poster. The approval of the rest of the co-authors will however be required. That being said, there should be a strong reason to refuse such request. We encourage dissemination and we should work together to get it done and disseminated to the broader audience. We advice to focus each time into a specific section of the project, like the tool, miRNA, isomiRs … etc

* (Loren Pantano) I am currently organizing a small RNA collaborative retreat in Boston by October. If anyone is interested, let me know privately. The main idea is to bring together computational and experimental research with interactive sessions.
