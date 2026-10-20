# Genetic Testing
#bpt/genetics #bpt/racp_cls
- - -
### Overview
Genetic tests can fall into five broad categories:
- Diagnostic - investigating _symptomatic_ individuals for _specific_ diseases (e.g. _FBN1_ gene testing in an individual with clinical features of Marfan syndrome)
- Carrier - investigating an _asymptomatic_ individual who is at increased risk of being a carrier, often for reproductive reasons (e.g. _CFTR_ testing in a person at risk of being a carrier)
- Predictive - investigating an _asymptomatic_ individual who is at increased risk of a genetic condition _prior_ to the onset of symptoms (e.g. _HTT_ testing in an adult person with a family history of Huntington disease)
- Prenatal - investigating a fetus/pregnant woman at increased risk of a genetic conditoin prior to birth (e.g. prenatal testing of _Dystrophin_ gene variants. in a female carrier of DMD)
- Pharmacogenetic - investigating a person with a disease using a medication to identify variants affecting that medication (e.g. CYP2C9 and warfarin)

#### Note re: Incidental Findings
The likelihood of identifying an incidental finding increases significantly as more regions of the human genome undergo sequencing analysis.
- - -
### Chromosome Testing
#### Karyotype
![](Genetic%20Testing/image.png)
Analysis of the entire set of chromosomes, which are arrested at the metaphase using drugs such as colchicine. These are then stained to elicit banding patterns, paired, and arranged by size. In general, anomalies that are detectable through karyotyping will produce a clear phenotypic change.

The _acrocentric_ chromosomes (13, 14, 15, and 21) have the centromeres very close to one end, such that the p-arm is very much shorter than the q-arm. These p-arms carry the genes that encode the large ribosomal subunits. 

Karyotype nomenclature:
- $Number$, XY/XX -> # of chromosomes + sex chromosomes
- t(a; b) -> translocation between chromosomes a and b
- (pA;qB) -> short arm of chromosome A, long arm of B
- der(a, b) -> derivative fusion chromosome from a and b 
- dup(a)(pApB) -> duplication of the section on chromosome a’s p-arm between bands A and B

Karyotyping is good for detecting:
- Polyploidy
- Aneuploidy
- Translocations
- Inversions
- Rings
- Copy number variants (CNVs) >4000 base pairs in size (can detect variations in banding)

Karyotyping _cannot_ detect:
- Small CNVs
- Sequence variants in genes

#### Fluorescent In Situ Hybridisation
![](Genetic%20Testing/image%202.png)
Analysis based on fluorescently labelled DNA probes, one of which is a control that hybridises with the target chromosome, and the second of which hybridises to the target location of interest (e.g. in this case chromosome 22 and region 22q11.2 respectively). The probes then fluoresce with the relevant colour, identifying duplications or deletions.

Advantages of FISH:
- Simple and quick
- Targeted to region of choice
- Detects smaller chromosome deletions/duplications not visible on karyotyping (e.g. DiGeorge syndrome, Williams syndrome)

Disadvantages of FISH:
- Cannot detect very small CNVs or sequence variants in genes

#### Microarray
Genome-wide, high-resolution chromosome analysis, utilising a microarray chip with thousands of short DNA sequences in a precise grid. Once the patient’s DNA is digested and labelled, it can then hybridise with the matching probe on the chip, which is then scanned to detect the amount of fluorescence on each probe, allowing for detections of copy number variants and (with SNP-based assays) copy neutral changes (e.g. uniparental disomy).

This method is unable to detect structural rearrangements or sequence variants in genes.
![](Genetic%20Testing/image%203.png)
- - -
### Gene Testing
#### Polymerase Chain Reaction
The fundamental basis of all single-gene tests. A method of copying target regions of DNA, utilising three steps:
- Heat based denaturation
- Annealing, where target sequences bind to primers -> gives PCR its specificity
- Elongation, where _taq_ polymerase elongates the relevant DNA, leading to exponential amplification of DNA quantities -> gives PCR its sensitivity 

This requires:
- DNA target template
- Two primers - complementary in the forward and reverse direction to the 3’ end of each strang
- _Taq_ polymerase to synthesise new strands
- Bases
- Buffer solution

#### Sanger Sequencing
Gold standard test for single genes, capturing the exons of one gene at a time. Utilises components of PCR, with additional chain terminating dideoxynucleotides, creating sequential DNA sequences which are separated by capillary electrophoresis at a resolution of one base, which allow for the identification of specific sequences.

#### Genomic Testing
Can be targeted, whole exome, or whole genome. Excellent for detecting single nucleotide variants. Accurate, but can yield _too_ much information. Relies on the existence of reference panels -> need to ask defined questions to obtain meaningul answers. 
![](Genetic%20Testing/image%204.png)

#### Multiplex Ligation Dependent Probe Ampification
A quantitative method utilising a small pool of custom proves to target specific genoimc regions to identify small copy number variants.

#### Southern Blot
Generally superseded by triplet primed PCR and automated analysis. Useful for deletions, duplications, and nucleotide repeat expansions (e.g. _DMPK_, _FRAX_, _HTT_, _SCA1_)
- - -
### Imprinting Testing
#### Methylation-Specific MLPA
Quantitative method with methylation profiling which is able to clarify parental alleles in the case of uniparental disomy. Able to detect both small CNVs/deletions/duplications and epigenetic/methylation alterations. Best first-line test for imprinting disorders. 
- - -
