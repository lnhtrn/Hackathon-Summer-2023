# University of Rochester Biomedical Data Science Hackathon Summer 2023
<<<<<<< HEAD
=======
The hackathon is now completed and final scores are posted.
>>>>>>> 87186e3cbb3a155bcd6da1e0f50798f754464c8c

Team *athena*'s submission for the University of Rochester Biomedical Data Science Hackathon Summer 2023. We implemented and optimized DoubletDetection to predict doublet cells in single cell sequencing data, achieving a MCC score of 0.556, [highest score amongst Undergraduate Division](https://www.linkedin.com/feed/update/urn:li:activity:7100202352468455424/).


# Overview
Single cell RNA sequencing (scRNA-seq) is a recently developed technology platform used to measure gene expression from thousands of individual cells. scRNA-seq is transforming biology and medicine as it enables studies of cell-heterogeneity, identification of cell types and subpopulations in complex tissues and measuring cell transformations during development. However, scRNA-seq also has a number of analysis challenges commonly encountered in data science. One of the main challenges is that the read count matrix (genes x cells) is sparse in that it contains many zeros due to technological limitations (e.g. only a thousands genes have count data from an individual cell even though many more genes are expressed in that cell). For an overview of how scRNA-seq data is obtained and best practices for scRNA-seq analysis see Huemos et al. (2023, [PMC10066026](https://www.nature.com/articles/s41576-023-00586-w)).

The goal of this hackathon is to identify doublets in scRNA-seq data. Doublets or multiplets are cases where gene expression count data is generated from two or more cells rather than a single cell. This occurs when a unique molecular identifier (UMI) is associated with two cells in a liquid droplet rather than one, resulting in a mixture of expression from both cells. There are a variety of ways in which doublets can be detected, most often by cells that appear to show a mixture of expression patterns from two different cell types. Doublets involving the same cell type are much more difficult to detect. One's ability to detect doublets depends on how one deals with sparse data, normalization and cell type clustering. For a review of methods see Xi and Li (2021, [PMC7897250](https://doi.org/10.1016/j.cels.2020.11.008)). Accurate detection of doublets remains a significant challenge and no single method outperforms all others.
<<<<<<< HEAD
=======

# Data
See [data description](Data.Description.md) for details.

   # Prizes
   
1.  First place in each division: $300 + $75 x (team size)
2.  Second place in each division: 0 + $50 x (team size)
  
# Winners!
**Congratulations to the winning teams:**
 * 1st place Undergraduate division- athena
 * 2nd place Undergraduate division- MLbeginners
 
 * 1st place Open division - CookieMonster 
 * 2nd place Open division- DMMH

If your team's final MCC was >0.0012, you will receive a prize! 
* All individuals who participated in the following teams will receive a prize for your score: CookieMonster, DMMH, MF_ZS, TheSelfishFruitFlies, athena, AveragePitaEnjoyers, DataMedics, MLbeginners, NW_KD_EL, CIV, ZhongZaiCanYu, GAC Soldiers, ant_on, wizard,DrJones

In order to claim your prize, you will need to fill out a [post-competition survey](https://forms.gle/7cgLDG6nPKQUc8tc9) and [prize information form](https://forms.gle/L7cHJQBXYBpy3sU37).


# Feedback and post-event information
Thank you for participating in this competition! We hope that you enjoyed the event. Please give us feedback so that we can improve future events. All teams that submit predictions may receive a participation certificate. Please e-mail alarracu at bio.rochester.edu for your certificate.

**Fill out the post-competition [survey](https://forms.gle/7cgLDG6nPKQUc8tc9).** 
* If your team submitted predictions and you would like to receive a certificate of participation, please e-mail alarracu@bio.rochester.edu. 
* Some of the winning teams will present their approach to the hackathon in an upcoming meeting of the GIDS working group in life and biomedical data science. You are all invited. Details about the meeting will come via e-mail once it is scheduled.
>>>>>>> 87186e3cbb3a155bcd6da1e0f50798f754464c8c
