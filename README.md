#### Summary
In an effort to increase our understanding of the immune response to Lassa virus (LASV) and Ebola virus (EBOV), we are typing the human leukocyte antigen (HLA) genes from Lassa and Ebola patients, as well as healthy individuals.

We perform HLA typing using the Illumina TruSight HLA Sequencing Panel, which allows the isolation and amplification of 11 HLA loci (Class I HLA-A, -B, -C; Class II HLA-DRB1/3/4/5, -DQA1, -DQB1, -DPA1, -DPB1) using long range PCR. Amplicons are used to produce libraries using the Illumina Nextera protocol and sequenced on the Illumina MiSeq platform. HLA-optimized software is used to analyze sequence data, produce consensus sequences and compare them to the IMGT/HLA database for HLA genotype assignments.

To date, together with our collaborators at the Broad Institute we have sequenced and genotyped 370 samples from Lassa and Ebola unique patients as well as control samples from healthy individuals (55 Ebola, 203 Lassa and 97 controls), resulting in a total of 6248 alleles sequenced ([Obs_Total_alleles.csv](https://github.com/andersen-lab/lassa-ebola-hla/blob/master/Obs_Total_alleles.csv)). As groups, Ebola patients yielded 155 unique alleles, Lassa patients yielded 247 unique alleles and 178 unique alleles in the Control group ([Obs_Total_alleles_grouped.csv](https://github.com/andersen-lab/lassa-ebola-hla/blob/master/Obs_Total_alleles_grouped.csv)). The Lassa dataset includes genotype data from 45 deceased patients which we have used to make preliminary comparisons with the lassa survivor group. We continue to process and genotype more individuals and we will be releasing the data here as we generate it – stay tuned.

So far, the data suggest the presence of a high number of novel alleles (n=41) - that is alleles with no reference in the IMGT/HLA database ([novel_alleles.csv](https://github.com/andersen-lab/lassa-ebola-hla/blob/master/novel_alleles.csv)). ~20% of new alleles are found in the Class I and ~80% in the Class II HLA loci. The DQB1 and DPA1 loci have the highest numbers with 11 and 9 novel alleles, respectively. A novel allele of particular interest is the presence of a nonsynonymous mutation in the start codon (ATG to ACG) of the DPA1 loci (DPA1*03:01@2).

A comprehensive list of the 288 observed HLA alleles sequenced in the Lassa, Ebola and control groups (n=370) and their frequencies is presented in ([allele_frequencies.csv](https://github.com/andersen-lab/lassa-ebola-hla/blob/master/allele_frequencies.csv)). Thus far, the results of this project have contributed in the efforts to characterize the under-represented West African population in the IMGT/HLA database, and most importantly, these results may shed light in understanding the contribution of specific HLA genotypes in association with outcomes of hemorrhagic fever infection in the West African population.

#### Allelic Frequencies(>5%)

| MHC-I| | |MHC-II| | |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Gene | Allele | Allelic Frequency | Gene | Allele | Allelic Frequency |
| HLA-A | A*020101 | 0.14| HLA-DPA1 | DPA1*020101 | 0.23 | 
| HLA-A | A*230101 | 0.13| HLA-DPA1 | DPA1*020202 | 0.2 | 
| HLA-A | A*330301 | 0.09| HLA-DPA1 | DPA1*020108 | 0.19 | 
| HLA-A | A*300101 | 0.09| HLA-DPA1 | DPA1*010301 | 0.1 | 
| HLA-A | A*300201 | 0.09| HLA-DPA1 | DPA1*030101 | 0.06 | 
| HLA-A | A*330101 | 0.06| HLA-DPA1 | DPA1*0301@2 | 0.06 | 
| HLA-A | A*030101 | 0.05| HLA-DPB1 | DPB1*010101 | 0.43 | 
| HLA-B | B*350101 | 0.13| HLA-DPB1 | DPB1*1050101 | 0.06 | 
| HLA-B | B*530101 | 0.11| HLA-DPB1 | DPB1*170101 | 0.05 | 
| HLA-B | B*420101 | 0.07| HLA-DPB1 | DPB1*010102 | 0.05 | 
| HLA-B | B*580101 | 0.06| HLA-DQA1 | DQA1*010201 | 0.21 | 
| HLA-B | B*450101 | 0.06| HLA-DQA1 | DQA1*050501 | 0.19 | 
| HLA-B | B*440301 | 0.06| HLA-DQA1 | DQA1*040101 | 0.17 | 
| HLA-B | B*780101 | 0.06| HLA-DQA1 | DQA1*030301 | 0.15 | 
| HLA-B | B*070201 | 0.05| HLA-DQA1 | DQA1*020101 | 0.06 | 
| HLA-B | B*150301 | 0.05| HLA-DQB1 | DQB1*040201 | 0.17 | 
| HLA-C | C*040101 | 0.21| HLA-DQB1 | DQB1*031901 | 0.16 | 
| HLA-C | C*160101 | 0.18| HLA-DQB1 | DQB1*050101 | 0.13 | 
| HLA-C | C*170101 | 0.09| HLA-DQB1 | DQB1*020201 | 0.13 | 
| HLA-C | C*030202 | 0.07| HLA-DQB1 | DQB1*030201 | 0.08 | 
| HLA-C | C*021001 | 0.05| HLA-DQB1 | DQB1*060201 | 0.08 | 
| | | | HLA-DQB1 | DQB1*060901 | 0.06 | 
| | | | HLA-DRB1 | DRB1*030201 | 0.17 | 
| | | | HLA-DRB1 | DRB1*130201 | 0.11 | 
| | | | HLA-DRB1 | DRB1*110102 | 0.07 | 
| | | | HLA-DRB1 | DRB1*110201 | 0.07 | 
| | | | HLA-DRB1 | DRB1*040501 | 0.06 | 
| | | | HLA-DRB1 | DRB1*070101 | 0.06 | 
| | | | HLA-DRB1 | DRB1*090102 | 0.06 | 
| | | | HLA-DRB3 | DRB3*020201 | 0.29 | 
| | | | HLA-DRB3 | DRB3*010102 | 0.24 | 
| | | | HLA-DRB3 | DRB3*030101 | 0.14 | 
| | | | HLA-DRB4 | DRB4*010301 | 0.12 | 
| | | | HLA-DRB4 | DRB4*010101 | 0.09 | 

\*Novel Alleles highlighted in <span style="color: red;">RED</span>.

![Allele Frequency](https://raw.githubusercontent.com/andersen-lab/lassa-ebola-hla/master/img/allelic_frequency.png)

![Counts per HLA Gene](https://raw.githubusercontent.com/andersen-lab/lassa-ebola-hla/master/img/counts.png)

**Disclaimer**. Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments – we’ll buy beers for #ResearchParasites that spot flaws and faults in the data and come up with improvements!

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
