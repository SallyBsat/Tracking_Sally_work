# Data of Protein/Modification ChIPseq

TO DO LIST

- Make list/file/repo/whatever that has the following information:
	1) Protein/Modification ChiPped
	2) How many **DIFFERENT** ChIPseq experiments there are for each protein/Modification
	3) How many ***DIFFERENT** cancer cell line do we have? What are those?
	4) How many cancer cell line are for each Protein/Modification ?


#### 1) The proteins and histone modifications being ChIPed are: (8 in total)
-RING1B
-RING1A
-CBX7
-H2AK119ub1/H2Aub1 (monoubiquitination)
-H3K27me3(trimethylation) and trimethylation of H3K27M (H3K27 mutant)
-EZH2
-SUZ12
-EED

#### 2) **DIFFERENT** ChIPseq experiments for each protein and histone modification being ChIPed:

**There are 6 different ChIP experiments for RING1B**
-RING1B : paper 1 -> 2 ChIPs
                  paper 2 -> 1 ChIP
                  paper 4 -> 2 ChIPs
                  paper 9 ->  1 ChIP
                  Total -> 6 ChIPs

**There is 1  ChIP experiment for RING1A**
-RING1A : paper 9 -> 1 ChIP

**There is 1  ChIP experiment for CBX7**
-CBX7 : paper 1 -> 1 ChIP

**There are 3 different ChIP experiments for H2A119ub1**
-H2AK119ub1 : paper 1 -> 1 ChIP
                           paper 4 -> 2 ChIPs
                           Total -> 3 ChIPs

**There are 14 different ChIP experiments for H3k27me3**
-H3K27me3 : paper 3 -> 4 ChIPs (H3K27M) 
                         paper 4 -> 2 ChIPs
                         paper 5 -> 1 ChIP
                         paper 6 -> 1 ChIP
                         paper 7 -> 3 ChIPs
                         paper 8 -> 2 ChIPs
                         paper 9 -> 1 ChIP
                         Total -> 14 ChIPs

**There are 5 different ChIP experiments for EZH2**
-EZH2: paper 5 -> 2 ChIPs
              paper 6 -> 1 ChIP
              paper 8 -> 2 ChIPs
              Total -> 5 ChIPs

**There are 5 different ChIP experiments for SUZ12**
-SUZ12: paper 5 -> 1 ChIP
                paper 6 -> 1 ChIP
                paper 7 -> 1 ChIP
                paper 8 -> 2 ChIPs
                Total -> 5 ChIPs

**There are 2 different ChIP experiments for EED**
-EED: paper 5 -> 1 ChIP
           paper 9 -> 1 ChIP
           Total -> 2 ChIPs


#### 3) Total cancer cell lines
***15 Different Cancer cell lines:*** 
-A673
-DIPG007
-DIPG012
-SF7761
-SF8628 
-MDA-MB-231
-T47D 
-H209
-DMS53
-16D
-42D
-DU145
-Lu130
-LNCaP-abl (abl)
-LNCaP

-A673, Ewing sarcoma cell line
-DIPG007, DIPG012, SF7761 and SF8628 are primary DIPG tumor cell line with K27M genotype(H3K27 Mutation)
-MDA-MB-231 cell line, Mammary gland adenocarcarcinoma epithelial cells derived from metastatic site
-T47D Small cell lung cancer cell line, Mammary gland ductal carcarcinoma epithelial cells derived from metastatic site
-H209
-DMS53, Small cell lung cancer cell line
-16D cell line, CRPC cell lines from Prostate adeno tumor.
-42D cell line, enzalutamide (ENZ)-resistant tNEPC from Prostate neuroendocrine tumor
-DU145, Human prostate cancer cell line
-Lu130, Small cell lung cancer cell line
-LNCaP-abl (abl) cell line , prostate cancer cells with androgen-independent genotype
-LNCaP cell line, prostate cancer cells with androgen-dependent genotype


#### 4) **DIFFERENT** cancer cell lines for each protein and histone modification being ChIPed.

##### **RING1B** :

***3 Different Cancer cell lines:*** 
-A673 -> ***Paper 1***
-T47D -> ***Paper 2, 4***
-MDA-MB-231 -> ***Paper 4***
-DU145 -> ***Paper 9***


##### **RING1A** :

***1  Cancer cell line:***
-DU145 -> ***Paper 9***


##### **CBX7** :

***1  Cancer cell line:***
-A673 -> ***Paper 1***

##### **H2AK119ub1** :

***3 Different Cancer cell lines:***
-A673 -> ***Paper 1*** 
-MDA-MB-231 -> ***Paper 4***
-T47D -> ***Paper 4***


##### **H3k27me3** :

***13 Different Cancer cell lines:***
-DIPG007 -> ***Paper 3***
-DIPG012 -> ***Paper 3***
-SF7761 -> ***Paper 3***
-SF8628 -> ***Paper 3***
-MDA-MB-231 -> ***Paper 4***
-T47D -> ***Paper 4***
-42D -> ***Paper 5***
-DU145 -> ***Paper 6***, ***Paper 9***
-Lu130 -> ***Paper 7***
-H209 -> ***Paper 7***
-DMS53 -> ***Paper 7***
-LNCaP-abl (abl) -> ***Paper 8***
-LNCaP -> ***Paper 8***


##### **EZH2** :

***5 Different Cancer cell lines:***
-16D -> ***Paper 5***
-42D -> ***Paper 5***
-DU145 -> ***Paper 6***
-LNCaP-abl (abl) -> ***Paper 8***
-LNCaP -> ***Paper 8***

##### **SUZ12** :

***5 Different Cancer cell lines:***
-42D -> ***Paper 5***
-DU145 -> ***Paper 6***
-Lu130 -> ***Paper 7***
-LNCaP-abl (abl) -> ***Paper 8***
-LNCaP -> ***Paper 8***


##### **EED** :

***2 Different Cancer cell lines:***
-42D -> ***Paper 5***
-DU145 -> ***Paper 9***


#### List of Papers:

##### [1-RING1B recruits EWSR1-FLI1 and cooperates in the remodelling of chromatin necessary for Ewing sarcoma tumorigenesis](https://www.science.org/doi/10.1126/sciadv.aba3058)

**[GSE131286](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE131286)**
**[SRP198531](https://www.ncbi.nlm.nih.gov/sra?term=SRP198531)**

(no input for CBX7)

**Organism:**
Homo sapiens


**Characteristics:**
cell line: A673  
cell type: Ewing sarcoma cell line
  
-ChIPseq_RING1B_Replicate1
-ChIPseq_RING1B_Replicate2
-ChIPseq_INPUTforRING1B_Replicate1
-ChIPseq_INPUTforRING1B_Replicate2
-ChIPseq_H2Aub1_Replicate1 
-ChIPseq_H2Aub1_Replicate2 
-ChIPseq_INPUTforH2Aub1_Replicate1
-ChIPseq_INPUTforH2Aub1_Replicate2 
-ChIPseq_CBX7
-ChIPseq_RING1B-shCTRL
-ChIPseq_INPUT-shCTRL

**H2Aub1 (H2A119ub)**


##### [2-Estrogen induces dynamic ERa and RING1B recruitment to control gene and enhancer activities in luminal breast cancer](https://www.science.org/doi/10.1126/sciadv.aaz7249?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)

**[GSE137579](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE137579)**
**[SRP222047](https://www.ncbi.nlm.nih.gov/sra?term=SRP222047)**

**Organism:**
Homo sapiens

**Characteristics:**
cell line: T47D  
cell type: Mammary gland ductal carcarcinoma epithelial cells derived from metastatic site


-T47D_shCtrl_0hr_input_chipseq
-T47D_shCtrl_0hr_RING1B_chipseq




##### [3-EZH2 is a potential therapeutic target for H3K27M-mutant pediatric gliomas](https://www.nature.com/articles/nm.4293)


**[GSE85387](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE85387)**
**[SRP081171](https://www.ncbi.nlm.nih.gov/sra?term=SRP081171)**

**Organism:**
Homo sapiens

**Characteristics:**
cell type: primary DIPG tumor cell line  (Diffuse intrinsic pontine glioma (DIPG)) 
genotype: K27M (H3K27M is a mutation wherein lysine 27 in H3 is substituted with methionine)
About 80% of DIPGs have a H3K27M mutation

**DIPG007 cells were obtained from the autopsy of a boy with glioblastoma multiforme.
DIPG012 was obtained from a biopsy in boy with anaplastic astrocytoma.**

-DIPG007 DMSO me3 (tumor sample: DIPG007)
-DIPG012 DMSO me3 (tumor sample: DIPG012)

**SF7761 and SF8628 are isolated from biopsied tissue from patients with DIPG.**

-SF7761 DMSO me3 (tumor sample: SF7761)
-SF8628 DMSO me3 (tumor sample: SF8628)

##### [4-Polycomb complexes associate with enhancers and promote oncogenic transcriptional programs in cancer through multiple mechanisms](https://www.nature.com/articles/s41467-018-05728-x)

**[GSE107176](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE107176)**
**[SRP125328](https://www.ncbi.nlm.nih.gov/sra?term=SRP125328)**

**Organism:**
Homo sapiens

**Characteristics:**
cell line: MDA-MB-231  
cell type: Mammary gland adenocarcarcinoma epithelial cells derived from metastatic site

-MDAMB231_Input_ChIP-seq
-MDAMB231_RING1B_ChIP-seq
-MDAMB231_H3K27me3_ChIP-seq
-MDAMB231_H2AK119ub1_ChIP-seq

**Characteristics:**
cell line: T47D  
cell type: Mammary gland ductal carcarcinoma epithelial cells derived from metastatic site

-T47D_Input_ChIP-seq
-T47D_RING1B_ChIP-seq
-T47D_H3K27me3_ChIP-seq
-T47D_H2AK119ub1_ChIP-seq


##### [5-An androgen receptor switch underlies lineage infidelity to drive neuroendocrine prostate cancer](https://www.nature.com/articles/s41556-021-00743-5)

**[GSE138460](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE138460)**

(no input except the double KO so maybe use our input)

**Organism:**
Homo sapiens

**Characteristics:**
cell line: CRPC (16D)  (Castration-resistant prostate cancer)
tumour type: Prostate adeno

-16D_EZH2_ChIPseq


**Characteristics:**
cell line: enzalutamide (ENZ)-resistant tNEPC 42D 
tumour type: Prostate neuroendocrine

-42D_EZH2_ChIPseq
-42D_H3K27Me3_ChIPseq

**Characteristics:**
cell line: Prostate cancer cell line 42D  
tumor type: ENZ-resistant CRPC-NE

-42D_SUZ12_ChIPseq
-42D_EED_ChIPseq

**tNEPC, treatment-induced neuroendocrine prostate cancer and it is a result of the transformation of prostate adenocarcinoma due to hormonal treatment mainly in advanced CRPC**

**ENZ-resistant cells were treated with ENZ (enzalutamide)**


**NOTE**
The below ChIPs have same cell lines which is 42D (The first 2 ChIPs are enzalutamide (ENZ)-resistant tNEPC and second 2 ChIPs are Prostate cancer cell lines)
-42D_EZH2_ChIPseq
-42D_H3K27Me3_ChIPseq
-42D_SUZ12_ChIPseq
-42D_EED_ChIPseq

##### [6-PHF19 mediated regulation of proliferation and invasiveness in prostate cancer](https://elifesciences.org/articles/51373)

**[GSE135623](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135623)**
**[SRP217915](https://www.ncbi.nlm.nih.gov/sra?term=SRP217915)**

**Organism:**
Homo sapiens

**Characteristics:**
cell line: DU145  
tissue: Human prostate cancer cell line

-ChIPseq_EZH2_CTR
-ChIPseq_SUZ12_CTR
-ChIPseq_H3K27me3_CTR
-ChIPseq_INPUT_CTR
-ChIPseq_EZH2_CTR_R2
-ChIPseq_SUZ12_CTR_R2
-ChIPseq_H3K27me3_CTR_R2
-ChIPseq_INPUT_CTR_R2


##### [7-PRC2 overexpression and PRC2-target gene repression relating to poorer prognosis in small cell lung cancer ](https://www.nature.com/articles/srep01911)

**[GSE99312](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99312)**
**[SRP108057](https://www.ncbi.nlm.nih.gov/sra?term=SRP108057)**

(no input except the double KO so maybe use our input)

**Organism:**
Homo sapiens

**Characteristics:**
cell line: Lu130  
cell type: Small cell lung cancer cell line

-Lu130_H3K27me3_ChIPSeq

**Characteristics:**
cell line: H209  
cell type: Small cell lung cancer cell line

-H209_H3K27me3_ChIPSeq

**Characteristics:**
cell line: DMS53  
cell type: Small cell lung cancer cell line

-DMS53_H3K27me3_ChIPSeq

**Characteristics:**
cell line: Lu130  
cell type: Small cell lung cancer cell line

-Lu130_Suz12_ChIPSeq


##### [8-EZH2 Oncogenic Activity in Castration-Resistant Prostate Cancer Cells Is Polycomb-Independent](https://www.science.org/doi/10.1126/science.1227604?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)


**[GSE39459](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE39459)**
**[SRP014457](https://www.ncbi.nlm.nih.gov/sra?term=SRP014457)**

**Organism:**
Homo sapiens

**Characteristics:**
cell line: LNCaP-abl (abl) prostate cancer cells  
genotype/variation: androgen-independent prostate cancer cells  

-EZH2_ChIPSeq_abl
-H3K27me3_ChIPSeq_abl
-SUZ12_ChIPSeq_abl
-inputDNA_abl

**Characteristics:**
cell line: LNCaP prostate cancer cells  
genotype/variation: androgen-dependent prostate cancer cells

-EZH2_ChIPSeq_LNCaP
-H3K27me3_ChIPSeq_LNCaP
-SUZ12_ChIPSeq_LNCaP
-inputDNA_LNCaP



##### [9-The Central Role of EED in the Orchestration of Polycomb Group Complexes](https://www.nature.com/articles/ncomms4127)

**[GSE42566](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE42566)**
**[SRP017337](https://www.ncbi.nlm.nih.gov/sra?term=SRP017337)**

(no input except the double KO so maybe use our input)

**Organism:**
Homo sapiens

**Characteristics:**
cell line: DU145 prostate cancer cells  
genotype/variation: control

-EED_Scr_ChIPSeq
-RING1A_CST_Scr_ChIPSeq
-RING1B_CST_Scr_ChIPSeq
-H3K27Me3_CST_Scr_ChIPSeq










**NOTE**
papers 5,7, and 9 have no input so maybe I should use our input., same thing for CBX7 in paper 1.
