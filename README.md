# Co-transcriptional splicing changes combine with reduced productive transcription initiation for cold-induced repression of FLC
# Robert Maple†, Govind Menon†, Susan Duncan , Anna Schulten, Maria Sindalovskaya, Hongchun Yang, Rebecca Bloomer, Martin Howard, Caroline Dean

Python and R code and associated data files used to perform data analysis, model parameter inference, and creating plots for figures in Maple et al., 2025. 

FLC_mRNA_ActD_Decay_Exp1_Dataset.xlsx.zip contains an Excel files containing the mRNA counts per unit area from FLC for the smFISHmRNA decay experiment, obtained as described in the Methods section of the paper and shown in Fig. 2B.

FLC_mRNA_ActD_Decay_Exp2_Dataset.xlsx.zip contains an Excel files containing the mRNA counts per unit area from FLC and PP2A for a second smFISHmRNA decay experiment, obtained as described in the Methods section of the paper.

rbloomer_flc_timecourse_NV-7D_relUBC_NVrepscombined.txt contains the qPCR timecourse data shown in Fig. S12.

25-08-28_RNAdecay_RNAnorm_2WT0.xlsx.zip contains the RNA decay measurements by qPCR used for the analysis in rna_decay_qpcr_analysis.ipynb, and shown in Fig. S14.

The Jupyter notebooks provided can be used to generate the following plots presented in the paper:  

Figures 1, S2, S12: spliced_unspliced_analysis.ipynb  

Figure 2, S13, S15, S16: smFISH_mRNA_decay_rates.ipynb  (Note: FLC_mRNA_ActD_Decay_Exp1_Dataset.xlsx.zip and FLC_mRNA_ActD_Decay_Exp2_Dataset.xlsx.zip must be unzipped to be used by smFISH_mRNA_decay_rates.ipynb)

Figure 3, S5: maple_et_al_plaNETseq_script.Rmd (Note: The necessary .bed files must be prepared first)

Figure 4, S6-S11: flc_intron1_model_parameter_inference.ipynb

Figure S14: rna_decay_qpcr_analysis.ipynb

