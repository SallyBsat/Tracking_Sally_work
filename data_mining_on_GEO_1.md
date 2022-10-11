# ChipSeq data mining of Polycomb factors on GEO
## AIM

#### Meeting on 24/06/2022
check for different ChipSeq datasets of polycomb factors RING1B, SUZ12, EZH1/2, EED, RYBP and the histone modiffication associated to them. Compare their ChipSeq profile across different tumor cell lines and check if there are any changes. Record the (GSE nb), (paper), and (SRA nb). (only huaman cancer cell line)

## RING1B

RING1B chipseq cancer cell lines 

### Paper 1

[==RING1B recruits EWSR1-FLI1 and cooperates in the remodelling of chromatin necessary for Ewing sarcoma tumorigenesis](https://www.science.org/doi/10.1126/sciadv.aba3058)


**[GSE131286](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131286)** (downloaded part of the results before but deleted again)

SRA

**[SRP198531](https://www.ncbi.nlm.nih.gov/sra?term=SRP198531)**

#### Comments

- This one looks good, download RING1B and H2Ak119Ub1 samples
- Take a note that CBX7 has been ChIPped, might come in handy.

### Paper 2
[==Estrogen induces dynamic ERa and RING1B recruitment to control gene and enhancer activities in luminal breast cancer](https://www.science.org/doi/10.1126/sciadv.aaz7249?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)


**[GSE137579](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE137579)**

SRA

**[SRP222047](https://www.ncbi.nlm.nih.gov/sra?term=SRP222047)**

#### Comments

- This one looks good, download RING1B in shCTRl experiments at 0Hr
- All the other ChIPs at different time points might be used as replicates, we have to discuss that.


### Paper 3 (same as paper 5 of SUZ12) -> reqiures a bit digging

[==EZH2 is a potential therapeutic target for H3K27M-mutant pediatric gliomas](https://www.nature.com/articles/nm.4293)

This SuperSeries is composed of the following SubSeries:

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [RNA-Seq - mouse cell lines]

[GSE85385](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85385)

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [ChIP-Seq mouse cell lines]

[GSE85386](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85386)

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [ChIP-Seq human cell lines]

[GSE85387](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85387)

#### Comments

- Probalby not that useful useful. The H3K27me3 reported here is a trimethylation but the Histone harbors a mutation (H3K27M).
- Maybe we can use the trimethylation in the four different human cancer cell line, so only this one [GSE85387](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85387)

### Paper 4 (miami guy)

[==Polycomb complexes associate with enhancers and promote oncogenic transcriptional programs in cancer through multiple mechanisms](https://www.nature.com/articles/s41467-018-05728-x)


**[GSE107176](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE107176)**

#### Comments

- No MCF10A cause it's an ephitelial cell line from a fibrocystic breast.
- OK T47D and MDAMB231 cell line for RING1B, H2AK119Ub1, H3K27me3

## SUZ12 

SUZ12 chipseq cancer cell lines 

### Paper 1 

[==An androgen receptor switch underlies lineage infidelity to drive neuroendocrine prostate cancer](https://www.nature.com/articles/s41556-021-00743-5)

**[GSE138460](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE138460)**

#### Comments

- Ok, SUZ12 and H3K27me3


### Paper 2 (same as paper 2 of EZH1/2)

[==PHF19 mediated regulation of proliferation and invasiveness in prostate cancer](https://elifesciences.org/articles/51373)

**[GSE135623](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135623)**

SRA

**[SRP217915](https://www.ncbi.nlm.nih.gov/sra?term=SRP217915)**

#### Comments

- Very similar prostate cancer cell line, download them anyway

### Paper 3


##### This SubSeries is part of SuperSeries:

[==PRC2 overexpression and PRC2-target gene repression relating to poorer prognosis in small cell lung cancer ](https://www.nature.com/articles/srep01911)

**[GSE99312](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99312)**

SRA

**[SRP108057](https://www.ncbi.nlm.nih.gov/sra?term=SRP108057)**


#### Comments

- 4 different cell lines, take all of them just for now.


##### SuperSeries: ==(data on geo only, no paper) 

==Gene repression and ChIP-seq in Human Small Cell Lung Cancer [*THIS IS THE SAME AS BEFORE!!!*]

**[GSE99316](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99316)** 

##### This SuperSeries is composed of the following SubSeries:

==Gene repression with H3K27me3 modification in human small cell lung cancer (data on geo only, no paper) [*THIS IS THE SAME AS BEFORE!!!*]

**[GSE43346](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE43346)**

[==PRC2 overexpression and PRC2-target gene repression relating to poorer prognosis in small cell lung cancer]() [*THIS IS THE SAME AS BEFORE!!!*]

**[GSE99312](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99312)**



### Paper 4 (same as paper 1 of EZH1/2)

##### This SubSeries is part of SuperSeries: ==(data on geo only, no paper, THIS IS THE [PAPER](https://pubmed.ncbi.nlm.nih.gov/23239736/))

==Genome-wide maps of PRC2 complex components and chromatin states in prostate cancer cell lines

**[GSE39459](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39459)**

SRA

**[SRP014457](https://www.ncbi.nlm.nih.gov/sra?term=SRP014457)**

#### Comments

- 2 different prostate cancer cell line, ok


##### SuperSeries: ==(data on geo only, no paper) 

==Role of PRC2 complex components in prostate cancer cell lines [*THIS IS THE SAME AS BEFORE!!!*]

**[GSE39461](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39461)**


##### This SuperSeries is composed of the following SubSeries: (==data on geo only, no paper)

 
**[GSE39452](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39452)**

==Expression data of EZH2-dependent genes in prostate cancer cell lines [*THIS IS THE SAME AS BEFORE!!!*]

**[GSE39459](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39459)**

==Genome-wide maps of PRC2 complex components and chromatin states in prostate cancer cell lines [*THIS IS THE SAME AS BEFORE!!!*]


### Paper 5 (same as paper 3 of RING1B) -> reqiures a bit digging

[==EZH2 is a potential therapeutic target for H3K27M-mutant pediatric gliomas](https://www.nature.com/articles/nm.4293) [*THIS IS THE SAME AS BEFORE!!!*]

This SuperSeries is composed of the following SubSeries:

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [RNA-Seq - mouse cell lines]

**[GSE85385](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85385)**

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [ChIP-Seq mouse cell lines]

**[GSE85386](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85386)**

EZH2 is a potential therapeutic target for H3K27M mutant paediatric gliomas [ChIP-Seq human cell lines]

**[GSE85387](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85387)**

### Paper 6 [*THIS IS NOT CHIPSEQ*]
[==Frequent switching of Polycomb repressive marks and DNA hypermethylation in the PC3 prostate cancer cell line](https://www.pnas.org/doi/10.1073/pnas.0806437105?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)

**[GSE12334](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE12334)**


##  EZH1/2

 EZH1/2 chipseq cancer cell lines 


### Paper 1 (same as paper 4 of SUZ12)
##### This SubSeries is part of SuperSeries: (==data on geo only, no paper)

==Expression data of EZH2-dependent genes in prostate cancer cell lines 

**[GSE39452](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39452)**


##### SuperSeries ==(data on geo only, no paper)

==Role of PRC2 complex components in prostate cancer cell lines 

This SuperSeries is composed of the following SubSeries: (==data on geo only, no paper)

 
**[GSE39452](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39452)**

==Expression data of EZH2-dependent genes in prostate cancer cell lines 

**[GSE39459](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39459)**

==Genome-wide maps of PRC2 complex components and chromatin states in prostate cancer cell lines

**[GSE39461](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39461)**

### Paper 2 (same as paper 2 of SUZ12)

[==PHF19 mediated regulation of proliferation and invasiveness in prostate cancer](https://elifesciences.org/articles/51373)

**[GSE135623](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135623)**

SRA

**[SRP217915](https://www.ncbi.nlm.nih.gov/sra?term=SRP217915)**


## EED

### Paper 1

[==The Central Role of EED in the Orchestration of Polycomb Group Complexes](https://www.nature.com/articles/ncomms4127)

**[GSE42566](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE42566)**

SRA

**[SRP017337](https://www.ncbi.nlm.nih.gov/sra?term=SRP017337)**






## RYBP
RYBP chipseq cancer cell lines 




### Things to take into consideration


**==A) How to think  during and after data mining**

 Here should think about the question and what I can do to represent it and should think about different ways to represent it like boxplot or heatmap or igv. What is the main question.


**==B) Terms to understand**


SRA is general and GSE is general
SRX is specific to each GSM 

SRA (SRP..) has many SRX
GSE has many GSM

here I need to save SRA and not SRX but I need SRX from SRA Run selector tp select the ones I am interested in in form of txt file showing metadata

In the beginning I saw that SRA leads me to the fastq files and GSM is assigned for every sample that has a .bw file for  a Chipseq experiment on geo so I thought that I can do the data mining from .bw files however I have to start from fastq files (pipeline) and use these files to generate my own .bw files using the pipeline.


**==C) what Diego wants me to do?**

1) Check change in binding profile of polycomb protein 
in maybe (CpG islands and promoter regions)

2) Call peaks , see in CpG island or promoter (but when I said call peaks Andrea told me I am mixing stuff when we were in the meeting )


**==D) Andrea told me about this tool about he has never read and used it before so he does not know if it is useful, it might help me in finding papers**


[A tool to find sequencing data and metadata from public databases](https://github.com/pachterlab/ffq)



CBX?



# Final Notes

1) Organize better this repo, use *Headers* in a more clear way, fix links. Here i don't know where one section starts and where it ends, it nedd to be more tidy and structured.
2) Good source of *data* types, seems like that there are some *different cancer cell* lines.
2) *DON'T COPY AND PASTE STUFF* (e.g: This SuperSeries is composed of the following SubSeries: (==data on geo only, no paper)), this not only doesn't mean anything to me, but it's also distrcting
	Remmeber that you have to present something and digest information for others, in this case, i had a hard time figure out where i had to look.
4) Good balance between *PRC1* and *PRC2* data!!
3) Carefully check that the experiement has *ChIPseq* data, otherwise don't report it.
4) *Avoid repetion* when possible and link again to the previous section, don't copy again GEO access code/SRA, it's confusing.

## TO DO LIST

- Make list/file/repo/whatever that has the following information:
	1) Protein/Modification ChiPped
	2) How many *DIFFERENT* ChIPseq experiments there are for each protein/Modification
	3) How many *DIFFERENT* cancer cell line do we have? What are those?
	4) How many cancer cell line are for each Protein/Modification ?

trial1

